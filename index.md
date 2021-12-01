@def title = "MSC"
@def tags = ["general", "code"]
@def hascode = true

# Guten Tag

\tableofcontents <!-- you can use \toc as well -->

## Who are we?

We are a group of (not that) young people who are interested in mathematics and scientific computing.

```julia
abstract type Point end
struct PointR2{T<:Real} <: Point
    x::T
    y::T
end
len(p::T) where {T <: Point} = sqrt(sum(getfield(p, η)^2 for η ∈ fieldnames(T)))
```

We talk about technology waves in English, German, and Mandarin.

@@colbox-blue
Here we go!
@@


~~~
<div class="row">
  <div class="container">
    <iframe src="https://open.spotify.com/embed/track/4N2qNs5FhQHZh4YtdIWy2v?utm_source=generator" width="100%" height="380" frameBorder="0" allowfullscreen="" allow="autoplay; clipboard-write; encrypted-media; fullscreen; picture-in-picture"></iframe>
  </div>
</div>
~~~