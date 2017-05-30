# Guppy
Graph database intended for OLAP implementing Tinkerpop and designed to run on GPUs, specifically using mapd-core



## Goals

I want to basically end up with a Titan/Janusgraph-like system backed by mapd-core. The graph framework should be able to leverage the features that mapd-core provides instead of simply using it to stash data. I do also want to expose features the CUDA ecosystem can provide via Gremlin to really leverage the GPUs involved. Also a few things regarding mapd-core, I want to make sure that users can enable either gpu+cpu or cpu-only mode as well as packaging up mapd-core so that users have an easier time building this project.
