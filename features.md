---
title: What RESTHeart can do
permalink: "/features"
layout: page
---

<div class="row mt-4">
    <article class="mt-4 mt-lg-0 col-lg-4 zoom">
        <div class="card newsText text-justified h-100 w-100">
            <div class="card-body">
                <h5 class="card-title">
                    <h2><a href="{{ "/use-cases/rest-api" | prepend: site.baseurl }}">Full support of MongoDB</a></h2>
                </h5>
                <div>RESTHeart unlocks <strong>all the features</strong> of MongoDB. </div>
                <div class="mt-1">
                    Also supports <strong>Mongo Atlas</strong>, <strong>AWS DocumentDB</strong> and <strong>Azure Cosmos DB</strong>
                </div>
            </div>
            <div class="d-flex w-100 justify-content-end">
                <a class="btn btn-m" href="{{ "/use-cases/rest-api" | prepend: site.baseurl }}">Read More</a>
            </div>
        </div>
    </article>
    <article class="mt-4 mt-lg-0 col-lg-4 zoom">
        <div class="card newsText text-justified h-100 w-100">
            <div class="card-body">
                <h5 class="card-title">
                    <h2><a href="{{ "/docs/setup" | prepend: site.baseurl }}">Docker</a></h2>
                </h5>
                <div>
                    RESTHeart is available as a docker image. The service is lightweight and full stateless thus ideal for on-the-cloud deployments.
                    <a class="mt-1" href="https://hub.docker.com/r/softinstigate/restheart">
                        <img height="27" class="align-top rounded sm-2 mt-2 xs-2 img-responsive" alt="Docker Pulls"
                            src="https://img.shields.io/docker/pulls/softinstigate/restheart.svg?style=for-the-badge">
                    </a>
                </div>
            </div>
            <div class="d-flex w-100 justify-content-end">
                <a class="btn btn-m" href="{{ "/docs/setup" | prepend: site.baseurl }}">Read More</a>
            </div>
        </div>
    </article>
    <article class="mt-4 mt-lg-0 col-lg-4 zoom">
        <div class="card newsText text-justified h-100 w-100">
            <div class="card-body">
                <h5 class="card-title">
                    <h2><a href="{{ "/docs/security/overview/#understanding-restheart-security" | prepend: site.baseurl }}">Battle-tested Security</a></h2>
                </h5>
                <div><strong>Authentication</strong> and <strong>Authorization</strong> provided by its security layer. Security can be easily customized thanks to its pluggable architecture.
                </div>
            </div>
            <div class="d-flex w-100 justify-content-end">
                <a class="btn btn-m" href="{{ "/docs/security/overview/#understanding-restheart-security" | prepend: site.baseurl }}">Read More</a>
            </div>
        </div>
    </article>
</div>

<div class="row mt-4">
    <article class="mt-4 mt-lg-0 col-lg-12 zoom">
        <div class="card newsText text-justified h-100 w-100">
            <div class="card-body">
                <h5 class="card-title">
                    <h2><a href="{{ "/docs/plugins/overview/" | prepend: site.baseurl }}">Extensible with Plugins</a></h2>
                </h5>
                <div>
                    Extend RESTHeart via <strong>Plugins</strong> to <strong>transform</strong>, <strong>check</strong> and <strong>intercept</strong> requests and responses, executes <strong>hooks</strong> after a request completes and implement <strong>Web Services</strong>.
                </div>
                <div class="bs-callout bs-callout-info">
                    Plugins makes RESTHeart one of the most effective development platform with the majority of API available out-of-the-box and a simple way adding custom business logic.
                </div>
                <div>
                    Creating a plugin is as simple as implementing a java interface and copying the jar in the <i>plugins</i> directory 
                    <span class="small">(simplified deplyment available form RESTHeart Platform v5)</span>
                </div>
            </div>
            <div class="d-flex w-100 justify-content-end">
                <a class="btn btn-m" href="{{ "/docs/plugins/overview/" | prepend: site.baseurl }}">Read More</a>
            </div>
        </div>
    </article>
</div>

<div class="row mt-4">
    <article class="mt-4 mt-lg-0 col-lg-4 zoom">
        <div class="card newsText text-justified h-100 w-100">
            <div class="card-body">
                <h5 class="card-title">
                    <h2><a href="{{ "/docs/read-docs" | prepend: site.baseurl }}">Read JSON documents</a></h2>
                </h5>
                <div>
                Read JSON documents with GET requests, specifying MongoDB queries and projection options; deal with large result sets with pagination.
                </div>
            </div>
            <div class="d-flex w-100 justify-content-end">
                <a class="btn btn-m" href="{{ "/docs/read-docs" | prepend: site.baseurl }}">Read More</a>
            </div>
        </div>
    </article>
    <article class="mt-4 mt-lg-0 col-lg-4 zoom">
        <div class="card newsText text-justified h-100 w-100">
            <div class="card-body">
                <h5 class="card-title">
                    <h2><a href="{{ "/docs/write-docs" | prepend: site.baseurl }}">Write JSON documents</a></h2>
                </h5>
                <div>
                    Create, modify and delete JSON documents with POST, PUT, PATCH and DELETE requests. Use <strong>bulk requests</strong> to deal with multiple documents in one shot.
                </div>
            </div>
            <div class="d-flex w-100 justify-content-end">
                <a class="btn btn-m" href="{{ "/docs/write-docs" | prepend: site.baseurl }}">Read More</a>
            </div>
        </div>
    </article>
    <article class="mt-4 mt-lg-0 col-lg-4 zoom">
        <div class="card newsText text-justified h-100 w-100">
            <div class="card-body">
                <h5 class="card-title">
                    <h2>
                        <a href="{{ "/docs/files" | prepend: site.baseurl }}">Binary data</a>
                    </h2>
                </h5>
                <div>
                Complete binary files management to create, read and delete even huge files with MongoDB’s GridFS. RESTHeart supports Web Caching and automatically saves bandwith.
                </div>
            </div>
            <div class="d-flex w-100 justify-content-end">
                <a class="btn btn-m" href="{{ "/docs/files" | prepend: site.baseurl }}">Read More</a>
            </div>
        </div>
    </article>
</div>

<div class="row mt-4">
    <article class="mt-4 mt-lg-0 col-lg-4 zoom">
        <div class="card newsText text-justified h-100 w-100">
            <div class="card-body">
                <h5 class="card-title">
                    <h2><a href="{{ "/docs/aggregations" | prepend: site.baseurl }}">Aggregations</a></h2>
                </h5>
                <div>
                    Define and execute parametric <strong>Aggregations</strong>, supporting both map-reduce and aggregation pipelines.
                </div>
            </div>
            <div class="d-flex w-100 justify-content-end">
                <a class="btn btn-m" href="{{ "/docs/aggregations" | prepend: site.baseurl }}">Read More</a>
            </div>
        </div>
    </article>
    <article class="mt-4 mt-lg-0 col-lg-4 zoom">
        <div class="card newsText text-justified h-100 w-100">
            <div class="card-body">
                <h5 class="card-title">
                    <h2><a href="{{ "/docs/change-streams/" | prepend: site.baseurl }}">Real-time data</a></h2>
                </h5>
                <div>
                    Handle hundreds of thousands of clients with Change Streams via WebSocket.
                </div>
            </div>
            <div class="d-flex w-100 justify-content-end">
                <a class="btn btn-m" href="{{ "/docs/change-streams/" | prepend: site.baseurl }}">Read More</a>
            </div>
        </div>
    </article>
    <article class="mt-4 mt-lg-0 col-lg-4 zoom">
        <div class="card newsText text-justified h-100 w-100">
            <div class="card-body">
                <h5 class="card-title">
                    <h2>
                        <a href="{{ "/docs/transactions" | prepend: site.baseurl }}">Transactions</a>
                    </h2>
                </h5>
                <div>
                Execute requests in multi-document <strong>ACID transactions</strong>.
                </div>
            </div>
            <div class="d-flex w-100 justify-content-end">
                <a class="btn btn-m" href="{{ "/docs/transactions" | prepend: site.baseurl }}">Read More</a>
            </div>
        </div>
    </article>
</div>

<div class="row my-4">
    <article class="mt-4 mt-lg-0 col-lg-4 zoom">
        <div class="card newsText text-justified h-100 w-100">
            <div class="card-body">
                <h5 class="card-title">
                    <h2><a href="{{ "/docs/json-schema-validation/" | prepend: site.baseurl }}">Data validation</a></h2>
                </h5>
                <div>Validate write requests with <strong>JSON Schema</strong>. RESTHeart extends MongoDB support of JSON Schema to apply and reuse definitions stored in the internal schema store collection.
                </div>
            </div>
            <div class="d-flex w-100 justify-content-end">
                <a class="btn btn-m" href="{{ "/docs/json-schema-validation/" | prepend: site.baseurl }}">Read More</a>
            </div>
        </div>
    </article>
    <article class="mt-4 mt-lg-0 col-lg-4 zoom">
        <div class="card newsText text-justified h-100 w-100">
            <div class="card-body">
                <h5 class="card-title">
                    <h2>
                        <a href="{{ "docs/mgmt/dbs-collections/" | prepend: site.baseurl }}">DB Managment API</a>
                    </h2>
                </h5>
                <div>The API allows managing db resources, creating, deleting db and collection, defining indexes and apply plugins via resource metadata.</div>
            </div>
            <div class="d-flex w-100 justify-content-end">
                <a class="btn btn-m" href="{{ "docs/mgmt/dbs-collections/" | prepend: site.baseurl }}">Read More</a>
            </div>
        </div>
    </article>
    <article class="mt-4 mt-lg-0 col-lg-4 zoom">
        <div class="card newsText text-justified h-100 w-100">
            <div class="card-body">
                <h5 class="card-title">
                    <h2>
                        <a href="{{ "/docs/csv" | prepend: site.baseurl }}">Upload data from CSV files</a>
                    </h2>
                </h5>
                <div>The CSV Uploader Service allows importing data from a CSV file into a MongoDB collection.</div>
            </div>
            <div class="d-flex w-100 justify-content-end">
                <a class="btn btn-m" href="{{ "/docs/csv" | prepend: site.baseurl }}">Read More</a>
            </div>
        </div>
    </article>
</div>

{: .bs-callout.bs-callout-info}
Read more about the background of our product on <a href="https://medium.com/softinstigate-team/the-origins-of-our-product-9ed6978c9448">The origins of RESTHeart</a>