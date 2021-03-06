---
layout: page-full-width
title: Community Projects
---

Akka has a vibrant and passionate user community, the members of which have
created many independent projects using Akka as well as extensions to it.

The list on this page is contributed and maintained by the community, so
credit, blame, feature requests and so on should be directed at the respective
individuals or projects. Discussion about these projects is very welcome on the
[akka-dev mailing list](https://groups.google.com/forum/#!forum/akka-dev),
especially if the project in question does not have a forum of its own.

If you find something that is outdated or missing please submit a pull request by
[editing](https://github.com/akka/akka.github.com/edit/master/community/index.md)
this page, following the style shown in the example below.  We welcome all
entries, but we also reserve the right to remove entries for any reason (for
example due to the project being dead or in violation of applicable law, but
we also do not tolerate any kind of abusive behavior).  Being listed here does
not represent an endorsement by or affiliation with Typesafe, Inc. or the Akka
open-source project.

<p class="notice">
This page is currently being created: we have seeded it with those projects
which were previously listed as community projects selected by the Akka team.
Now we ask for your help in adding the missing meta-data (like for which
releases of Akka a certain project is available). We will eventually clean up
and remove those projects which have not been updated.
</p>

### Example Section

* **[Example Project Name](https://github.com/akka)** (by [Akka Team](https://github.com/akka))

  <table class="stats">
  <tr><td>Since Akka version:</td><td>0.5</td></tr>
  <tr><td>Latest Akka version:</td><td>2.3.0</td></tr>
  <tr><td>Latest Release:</td><td><code>"com.typesafe.akka" % "akka-actor_2.10" % "2.3.0"</code> (March 5, 2014)</td></tr>
  </table>

  Here you are very welcome to add a description of what the project or
  extension does, notices on where the artifacts are published, etc. The
  artifact listed under Latest Release should always be given in the Maven
  normal form (i.e. without the Scala binary version shortcut of using `%%`).
  It is also very good to include a link to the bug tracker, discussion forum
  and so on.

## Extensions to Akka

* **[Akka WebSocket](http://backchatio.github.com/hookup/)**

  <table class="stats">
  <tr><td>Since Akka version:</td><td>unknown</td></tr>
  <tr><td>Latest Akka version:</td><td>unknown</td></tr>
  <tr><td>Latest Release:</td><td>unknown</td></tr>
  </table>

* **[Akka AMQP Integration](https://github.com/momania/akka-amqp)**

  <table class="stats">
  <tr><td>Since Akka version:</td><td>unknown</td></tr>
  <tr><td>Latest Akka version:</td><td>unknown</td></tr>
  <tr><td>Latest Release:</td><td>unknown</td></tr>
  </table>

* **[Akka AMQP Durable Mailbox](https://github.com/drexin/akka-amqp-mailbox)**

  <table class="stats">
  <tr><td>Since Akka version:</td><td>unknown</td></tr>
  <tr><td>Latest Akka version:</td><td>unknown</td></tr>
  <tr><td>Latest Release:</td><td>unknown</td></tr>
  </table>

* **[Akka Protostuff Serialization](https://github.com/romix/akka-protostuff-serialization)**

  <table class="stats">
  <tr><td>Since Akka version:</td><td>unknown</td></tr>
  <tr><td>Latest Akka version:</td><td>unknown</td></tr>
  <tr><td>Latest Release:</td><td>unknown</td></tr>
  </table>

* **[Akka Quickser Serialization](https://github.com/romix/akka-quickser-serialization)**

  <table class="stats">
  <tr><td>Since Akka version:</td><td>unknown</td></tr>
  <tr><td>Latest Akka version:</td><td>unknown</td></tr>
  <tr><td>Latest Release:</td><td>unknown</td></tr>
  </table>

* **[Akka Kryo Serialization](https://github.com/romix/akka-kryo-serialization)**

  <table class="stats">
  <tr><td>Since Akka version:</td><td>unknown</td></tr>
  <tr><td>Latest Akka version:</td><td>unknown</td></tr>
  <tr><td>Latest Release:</td><td>unknown</td></tr>
  </table>

* **[Akka Quartz](https://github.com/theatrus/akka-quartz)**

  <table class="stats">
  <tr><td>Since Akka version:</td><td>unknown</td></tr>
  <tr><td>Latest Akka version:</td><td>unknown</td></tr>
  <tr><td>Latest Release:</td><td>unknown</td></tr>
  </table>

* **[Flow](https://github.com/jodersky/flow)** (by [Jakob Odersky](https://github.com/jodersky))

  <table class="stats">
  <tr><td>Since Akka version:</td><td>2.2.0</td></tr>
  <tr><td>Latest Akka version:</td><td>2.3.5</td></tr>
  <tr><td>Latest Release:</td><td><code>"com.github.jodersky" % "flow_2.10" % "2.0.4"</code> (August 18, 2014)<br/><code>"com.github.jodersky" % "flow_2.11" % "2.0.4"</code> (August 18, 2014)</td></tr>
  </table>

  Akka-IO extension for serial communication.

* **[Nucleus: RPC-like reactive system build on Akka IO](https://github.com/gideondk/nucleus)** (by [Gideon de Kok](https://github.com/gideondk))

  <table class="stats">
  <table class="stats">
    <tr><td>Since Akka version:</td><td>n/a</td></tr>
    <tr><td>Latest Akka version:</td><td>2.3.0</td></tr>
    <tr><td>Latest Release:</td><td><code>"nl.gideondk" %% "nucleus" % "0.1.2"</code> (March 12, 2014)</td></tr>
  </table>
  </table>

  Published to: `https://raw.github.com/gideondk/gideondk-mvn-repo/master`

* **[Sentinel: toolkit for creating reactive TCP clients & servers](https://github.com/gideondk/sentinel)** (by [Gideon de Kok](https://github.com/gideondk))

  <table class="stats">
  <table class="stats">
    <tr><td>Since Akka version:</td><td>n/a</td></tr>
    <tr><td>Latest Akka version:</td><td>2.3.0</td></tr>
    <tr><td>Latest Release:</td><td><code>"nl.gideondk" %% "sentinel" % "0.6.0"</code> (March 12, 2014)</td></tr>
  </table>
  </table>

  Published to: `https://raw.github.com/gideondk/gideondk-mvn-repo/master`

* **[rxmon: Monitoring akka applications with rx](https://github.com/vigdorchik/rxmon)** (by [Eugene Vigdorchik](https://github.com/vigdorchik))

  <table class="stats">
  <tr><td>Since Akka version:</td><td>2.2.4</td></tr>
  <tr><td>Latest Akka version:</td><td>2.3.0</td></tr>
  <tr><td>Latest Release:</td><td><code>"org.matmexrhino" % "rxmon_2.10" % "0.2.1"</code> (March 12 2014)</td></tr>
  </table>

  Published to bintray at "http://dl.bintray.com/vigdorchik/maven".

* **[Akka Tracing](https://github.com/levkhomich/akka-tracing)** (by [Lev Khomich](https://github.com/levkhomich))

  <table class="stats">
    <tr><td>Since Akka version:</td><td>2.3.0</td></tr>
    <tr><td>Latest Akka version:</td><td>2.3.2</td></tr>
    <tr><td>Latest Release:</td><td><code>"com.github.levkhomich" %% "akka-tracing-core" % "0.2"</code> (April 24, 2014)</td></tr>
  </table>

* **[Akka Zookeeper Cluster Seed: bootstrap your akka cluster seed nodes via zookeeper](https://github.com/sclasen/akka-zk-cluster-seed)** (by [Scott Clasen](https://github.com/sclasen))

  <table class="stats">
    <tr><td>Since Akka version:</td><td>2.3.3</td></tr>
    <tr><td>Latest Akka version:</td><td>2.3.3</td></tr>
    <tr><td>Latest Release:</td><td><code>"com.sclasen" %% "akka-zk-cluster-seed" % "0.0.5"</code> (June 3, 2014)</td></tr>
  </table>  

* **[Akka Data Replication](https://github.com/patriknw/akka-data-replication)** (by [Patrik Nordwall](https://github.com/patriknw))

  <table class="stats">
  <tr><td>Since Akka version:</td><td>2.3.3</td></tr>
  <tr><td>Latest Akka version:</td><td>2.3.6</td></tr>
  <tr><td>Latest Release:</td><td><code>"com.github.patriknw" %% "akka-data-replication" % "0.8"</code> (November 9, 2014)</td></tr>
  </table>

  A replicated in-memory data store and library of Conflict Free Replicated Data Types (CRDT).
  
  Published to bintray URL `http://dl.bintray.com/patriknw/maven`.

## Extensions to Spray

The Spray project is in the process of being merged into Akka as the new HTTP
module, see also [this news
item](http://www.typesafe.com/blog/typesafe-gets-sprayed). We also track
extensions to Spray on this page to make it clear that the transition of Spray does not
mean that these will be abandoned, we intend to support the merger of the Spray
and Akka eco-systems. The details remain to be determined, but there will be a
migration path from Spray 1.3 to Akka HTTP.

* **[binarycamp/spray-contrib](https://bitbucket.org/binarycamp/spray-contrib/src)** (by [Marcel Mojzis, Lukas Kostial](https://bitbucket.org/binarycamp))

  <table class="stats">
  <tr><td>Since spray version:</td><td>1.3.0</td></tr>
  <tr><td>Latest spray version:</td><td>1.3.0</td></tr>
  <tr><td>Latest Release:</td><td>none (to be published locally)</td></tr>
  </table>

  Extension modules built on top of spray.io: session management, OAuth 2.0 server (preview)


* **[SprayWebSockets](https://github.com/lihaoyi/SprayWebSockets)**

  <table class="stats">
  <tr><td>Since spray version:</td><td>unknown</td></tr>
  <tr><td>Latest spray version:</td><td>unknown</td></tr>
  <tr><td>Latest Release:</td><td>unknown</td></tr>
  </table>

  An implementation of a websocket server on top of spray.io


* **[NET-A-PORTER/spray-actor-per-request](https://github.com/NET-A-PORTER/spray-actor-per-request)**

  <table class="stats">
  <tr><td>Since spray version:</td><td>unknown</td></tr>
  <tr><td>Latest spray version:</td><td>unknown</td></tr>
  <tr><td>Latest Release:</td><td>unknown</td></tr>
  </table>

  Example spray application that uses the actor per request model


* **[SprayLearning](https://github.com/karthik20522/SprayLearning)**

  <table class="stats">
  <tr><td>Since spray version:</td><td>unknown</td></tr>
  <tr><td>Latest spray version:</td><td>unknown</td></tr>
  <tr><td>Latest Release:</td><td>unknown</td></tr>
  </table>

  Guide to learning Spray.io web framework


* **[S4 – Spray Slick Scala Start](https://github.com/jacobus/s4)**

  <table class="stats">
  <tr><td>Since spray version:</td><td>unknown</td></tr>
  <tr><td>Latest spray version:</td><td>unknown</td></tr>
  <tr><td>Latest Release:</td><td>unknown</td></tr>
  </table>

  Spray Slick Starter Stack


* **[Spray template for Heroku](https://github.com/matanster/spray-heroku)**

  <table class="stats">
  <tr><td>Since spray version:</td><td>unknown</td></tr>
  <tr><td>Latest spray version:</td><td>unknown</td></tr>
  <tr><td>Latest Release:</td><td>unknown</td></tr>
  </table>

  spray template project compatible with Heroku

* **[spray-aws – Spray AWS client](https://github.com/sclasen/spray-aws)** (by [Scott Clasen](https://github.com/sclasen))

  spray-client based clients for dynamodb, kinesis, and sqs.

  <table class="stats">
  <tr><td>Since Akka version:</td><td>2.1.0</td></tr>
  <tr><td>Latest Akka version:</td><td>2.3.0</td></tr>
  <tr><td>Latest Release:</td><td><code>"com.sclasen" % "spray-aws" % "0.2.5"</code> (March 12, 2014)</td></tr>
  </table>

  Published to Maven Central. Snapshots at the URL `https://oss.sonatype.org/content/repositories/snapshots`.

* **[Spray WebSocket](https://github.com/wandoulabs/spray-websocket)** (by [Wandou Labs](https://github.com/wandoulabs))

  <table class="stats">
  <tr><td>Since spray version:</td><td>1.3.0</td></tr>
  <tr><td>Latest spray version:</td><td>1.3.0</td></tr>
  <tr><td>Latest Release:</td><td>0.1 (to be published locally) </td></tr>
  </table>

  WebSocket implementation for Spray. Passed all Autobahn test cases (both for "ws" and "wss")

* **[Spray socket.io](https://github.com/wandoulabs/spray-socketio)** (by [Wandou Labs](https://github.com/wandoulabs))

  <table class="stats">
  <tr><td>Since spray version:</td><td>1.3.0</td></tr>
  <tr><td>Latest spray version:</td><td>1.3.0</td></tr>
  <tr><td>Latest Release:</td><td>0.1 (to be published locally) </td></tr>
  </table>

  socket.io implementation on Spray with cluster sharding.

* **[spray-funnel](https://github.com/galarragas/spray-funnel)**

  <table class="stats">
  <tr><td>Since spray version:</td><td>1.2.0</td></tr>
  <tr><td>Latest spray version:</td><td>1.3.1</td></tr>
  <tr><td>Latest Release:</td><td>1.0-RC3</td></tr>
  </table>

  Request throttling system for AKKA actors that has been specifically designed to support HttpRequest - HttpReply interactions. Can be used with Spray Client or Spray HTTP Server.

* **[spray-extensions](https://github.com/Jarlakxen/spray-extensions)** (by [Facundo Viale](https://github.com/Jarlakxen/))

  <table class="stats">
  <tr><td>Since spray version:</td><td>1.2.1</td></tr>
  <tr><td>Latest spray version:</td><td>1.2.1</td></tr>
  <tr><td>Latest Release:</td><td><code>"com.github.jarlakxen" %% "spray-extensions" % "1.0"</code> (May 26, 2014)</td></tr>
  </table>

  Useful extensions for spray: pagination, [scalate](http://scalate.fusesource.org/) integration, json filtering, etc.


## Plugins to Akka Persistence

Before adding a plugin to this list, it should have been tested for compatibility with the [plugin compatibility testkit](https://github.com/krasserm/akka-persistence-testkit).

### Journal plugins

* **[BDB plugin](https://github.com/bseibel/akka-persistence-bdb)** (by [Brandon Seibel](https://github.com/bseibel))

  <table class="stats">
  <tr><td>Since Akka version:</td><td>2.3.0-RC1</td></tr>
  <tr><td>Latest Akka version:</td><td>2.3.1</td></tr>
  <tr><td>Latest Release:</td><td><code>"com.github.bseibel" % "akka-persistence-bdb_2.10" % "1.0"</code></td></tr>
  </table>

  Published to bintray at the URL `http://dl.bintray.com/bseibel/release`.

* **[Cassandra plugin](https://github.com/krasserm/akka-persistence-cassandra/)** (by [Martin Krasser](https://github.com/krasserm))

  <table class="stats">
  <tr><td>Since Akka version:</td><td>2.3.0</td></tr>
  <tr><td>Latest Akka version:</td><td>2.3.6</td></tr>
  <tr><td>Latest Release:</td><td><code>"com.github.krasserm" % "akka-persistence-cassandra_2.10" % "0.3.4"</code><br><code>"com.github.krasserm" % "akka-persistence-cassandra_2.11" % "0.3.4"</code></td></tr>
  </table>

  Published to bintray at the URL `http://dl.bintray.com/krasserm/maven`.

  Compliant with [`akka-persistence-tck`](http://doc.akka.io/docs/akka/2.3.6/scala/persistence.html#plugin-tck).

* **[Kafka plugin](https://github.com/krasserm/akka-persistence-kafka/)** (by [Martin Krasser](https://github.com/krasserm))

  <table class="stats">
  <tr><td>Since Akka version:</td><td>2.3.4</td></tr>
  <tr><td>Latest Akka version:</td><td>2.3.6</td></tr>
  <tr><td>Latest Release:</td><td><code>"com.github.krasserm" % "akka-persistence-kafka_2.10" % "0.3.3"</code></td></tr>
  </table>

  Published to bintray at the URL `http://dl.bintray.com/krasserm/maven`.

  Compliant with <code>akka-persistence-testkit 0.3.4</code>.

* **[DynamoDB plugin](https://github.com/sclasen/akka-persistence-dynamodb/)** (by [Scott Clasen](https://github.com/sclasen))

  <table class="stats">
  <tr><td>Since Akka version:</td><td>2.3.0-RC4</td></tr>
  <tr><td>Latest Akka version:</td><td>2.3.0</td></tr>
  <tr><td>Latest Release:</td><td><code>"com.sclasen" % "akka-persistence-dynamodb_2.10" % "0.1"</code> (March 6, 2014)</td></tr>
  </table>

  Published to Maven Central. Snapshots at the URL `https://oss.sonatype.org/content/repositories/snapshots`.

* **[HBase plugin](https://github.com/ktoso/akka-persistence-hbase/)** (by [Konrad Malawski](https://github.com/ktoso))

  <table class="stats">
  <tr><td>Since Akka version:</td><td>2.3-SNAPSHOT</td></tr>
  <tr><td>Latest Akka version:</td><td>2.3.4</td></tr>
  <tr><td>Latest Release:</td><td><code>"pl.project13.scala" % "akka-persistence-hbase_2.10" % "0.4.1"</code><br/>
                                  <code>"pl.project13.scala" % "akka-persistence-hbase_2.11" % "0.4.1"</code></td></tr>
  </table>

* **[MapDB plugin](https://github.com/drexin/akka-persistence-mapdb/)** (by [Dario Rexin](https://github.com/drexin))

  <table class="stats">
  <tr><td>Since Akka version:</td><td>2.3.0-RC1</td></tr>
  <tr><td>Latest Akka version:</td><td>2.3.0-RC1</td></tr>
  <tr><td>Latest Release:</td><td>none (to be published locally)</td></tr>
  </table>

* **[MongoDB plugin](https://github.com/ddevore/akka-persistence-mongo/)** (by [Duncan DeVore](https://github.com/ddevore))

  <table class="stats">
  <tr><td>Since Akka version:</td><td>2.3.0</td></tr>
  <tr><td>Latest Akka version:</td><td>2.3.5</td></tr>
  <tr><td>Latest Release:</td><td><code>"com.github.ddevore" % "akka-persistence-mongo-casbah_2.10"  % "0.7.4-SNAPSHOT"</code><br/><code>"com.github.ddevore" % "akka-persistence-mongo-casbah_2.11"  % "0.7.4-SNAPSHOT"</code></td></tr>
  </table>

  Published to Maven Central. Snapshots at the URL `https://oss.sonatype.org/content/repositories/snapshots`.

  Compliant with <code>akka-persistence-testkit 0.3.4</code>.

* **[MongoDB plugin](https://github.com/scullxbones/akka-persistence-mongo/)** (by [Brian Scully](https://github.com/scullxbones))

  <table class="stats">
  <tr><td>Since Akka version:</td><td>2.3.0</td></tr>
  <tr><td>Latest Akka version:</td><td>2.3.0</td></tr>
  <tr><td>Latest Release:</td><td><code>"com.github.scullxbones" % "akka-persistence-mongo-casbah_2.10" % "0.0.8"</code> (March 24, 2014)</td></tr>
  </table>

  Published to Maven Central.  Compliant with 0.0.3 of plugin compatibility testkit.

* **[In-Memory plugin for testing](https://github.com/michaelpisula/akka-journal-inmemory)** (by [Michael Pisula](https://github.com/michaelpisula))

  <table class="stats">
  <tr><td>Since Akka version:</td><td>2.3.0</td></tr>
  <tr><td>Latest Akka version:</td><td>2.3.0</td></tr>
  <tr><td>Latest Release:</td><td>"com.github.michaelpisula" %% "akka-persistence-inmemory" % "0.1.1" (May 09, 2014)</td></tr>
  </table>

* **[InMemory plugin](https://github.com/dnvriend/akka-persistence-inmemory)** (by [Dennis Vriend](https://github.com/dnvriend))

  <table class="stats">
  <tr><td>Since Akka version:</td><td>2.3.4</td></tr>
  <tr><td>Latest Akka version:</td><td>2.3.6</td></tr>
  <tr>
    <td>Latest Release:</td>
    <td>
      <code>"com.github.dnvriend" % "akka-persistence-inmemory_2.10" % "0.0.2"</code><br/>
      <code>"com.github.dnvriend" % "akka-persistence-inmemory_2.11" % "0.0.2"</code>
    </td>
  </tr>
  </table>
  
  Published to Maven Central. Compliant with <code>akka-persistence-testkit 0.3.4</code>.

* **[JDBC plugin](https://github.com/dnvriend/akka-persistence-jdbc)** (by [Dennis Vriend](https://github.com/dnvriend))

  <table class="stats">
  <tr><td>Since Akka version:</td><td>2.3.2</td></tr>
  <tr><td>Latest Akka version:</td><td>2.3.6</td></tr>
  <tr>
    <td>Latest Release:</td>
    <td>
      <code>"com.github.dnvriend" % "akka-persistence-jdbc_2.10" % "1.0.5"</code><br/>
      <code>"com.github.dnvriend" % "akka-persistence-jdbc_2.11" % "1.0.5"</code>
    </td>
  </tr>
  </table>
  
  Published to Maven Central. Compliant with <code>akka-persistence-testkit 0.3.4</code>.

* **[MySQL & PostgreSQL plugin](https://github.com/okumin/akka-persistence-sql-async)** (by [okumin](https://github.com/okumin))

  <table class="stats">
    <tr><td>Since Akka version:</td><td>2.3.6</td></tr>
    <tr><td>Latest Akka version:</td><td>2.3.6</td></tr>
    <tr><td>Latest Release:</td><td><code>"com.okumin" %% "akka-persistence-sql-async" % "0.1"</code> (Sep 30, 2014)</td></tr>
  </table>

  Published to Maven Central. Compliant with [`akka-persistence-tck`](http://doc.akka.io/docs/akka/2.3.6/scala/persistence.html#plugin-tck).

* **[Shared In-Memory Plugin](https://github.com/jdgoldie/akka-persistence-shared-inmemory/)** (by [Joshua Goldie](https://github.com/jdgoldie))

  <table class="stats">
  <tr><td>Since Akka version:</td><td>2.3.6</td></tr>
  <tr><td>Latest Akka version:</td><td>2.3.6</td></tr>
  <tr><td>Latest Release:</td><td><code>"com.github.jdgoldie" % "akka-persistence-shared-inmemory_2.10" % "1.0.15"</code><br><code>"com.github.jdgoldie" % "akka-persistence-shared-inmemory_2.11" % "1.0.15"</code></td></tr>
  </table>

  Published to bintray at the URL `http://dl.bintray.com/jdgoldie/maven`.

  In-memory implementations of the journal and snapshot store designed to work with multi-node and single-node unit tests.  Tested against `akka-persistence-tck-experimental` version 2.3.6


### Snapshot plugins

* **[HBase plugin](https://github.com/ktoso/akka-persistence-hbase/)** (by [Konrad Malawski](https://github.com/ktoso))

  <table class="stats">
  <tr><td>Since Akka version:</td><td>2.3-SNAPSHOT</td></tr>
  <tr><td>Latest Akka version:</td><td>2.3.4</td></tr>
  <tr><td>Latest Release:</td><td><code>"pl.project13.scala" % "akka-persistence-hbase_2.10" % "0.4.1"</code><br/>
                                  <code>"pl.project13.scala" % "akka-persistence-hbase_2.11" % "0.4.1"</code></td></tr>
  </table>

* **[MongoDB plugin](https://github.com/scullxbones/akka-persistence-mongo/)** (by [Brian Scully](https://github.com/scullxbones))

  <table class="stats">
  <tr><td>Since Akka version:</td><td>2.3.0</td></tr>
  <tr><td>Latest Akka version:</td><td>2.3.0</td></tr>
  <tr><td>Latest Release:</td><td><code>"com.github.scullxbones" % "akka-persistence-mongo-casbah_2.10" % "0.0.8"</code> (March 24, 2014)</td></tr>
  </table>

  Published to Maven Central.  Compliant with 0.0.3 of plugin compatibility testkit.

* **[MongoDB plugin](https://github.com/ddevore/akka-persistence-mongo/)** (by [Duncan DeVore](https://github.com/ddevore))

  <table class="stats">
  <tr><td>Since Akka version:</td><td>2.3.0</td></tr>
  <tr><td>Latest Akka version:</td><td>2.3.5</td></tr>
  <tr><td>Latest Release:</td><td><code>"com.github.ddevore" % "akka-persistence-mongo-casbah_2.10"  % "0.7.4-SNAPSHOT"</code><br/><code>"com.github.ddevore" % "akka-persistence-mongo-casbah_2.11"  % "0.7.4-SNAPSHOT"</code></td></tr>
  </table>

  Published to Maven Central. Snapshots at the URL `https://oss.sonatype.org/content/repositories/snapshots`.

  Compliant with <code>akka-persistence-testkit 0.3.4</code>.

* **[Cassandra plugin](https://github.com/krasserm/akka-persistence-cassandra/)** (by [Martin Krasser](https://github.com/krasserm))

  <table class="stats">
  <tr><td>Since Akka version:</td><td>2.3.2</td></tr>
  <tr><td>Latest Akka version:</td><td>2.3.6</td></tr>
  <tr><td>Latest Release:</td><td><code>"com.github.krasserm" % "akka-persistence-cassandra_2.10" % "0.3.4"</code><br><code>"com.github.krasserm" % "akka-persistence-cassandra_2.11" % "0.3.4"</code></td></tr>
  </table>

  Published to bintray at the URL `http://dl.bintray.com/krasserm/maven`.

  Compliant with [`akka-persistence-tck`](http://doc.akka.io/docs/akka/2.3.6/scala/persistence.html#plugin-tck).

* **[Kafka plugin](https://github.com/krasserm/akka-persistence-kafka/)** (by [Martin Krasser](https://github.com/krasserm))

  <table class="stats">
  <tr><td>Since Akka version:</td><td>2.3.4</td></tr>
  <tr><td>Latest Akka version:</td><td>2.3.6</td></tr>
  <tr><td>Latest Release:</td><td><code>"com.github.krasserm" % "akka-persistence-kafka_2.10" % "0.3.3"</code></td></tr>
  </table>

  Published to bintray at the URL `http://dl.bintray.com/krasserm/maven`.

  Compliant with <code>akka-persistence-testkit 0.3.4</code>.

* **[InMemory plugin](https://github.com/dnvriend/akka-persistence-inmemory)** (by [Dennis Vriend](https://github.com/dnvriend))

  <table class="stats">
  <tr><td>Since Akka version:</td><td>2.3.4</td></tr>
  <tr><td>Latest Akka version:</td><td>2.3.6</td></tr>
  <tr>
    <td>Latest Release:</td>
    <td>
      <code>"com.github.dnvriend" % "akka-persistence-inmemory_2.10" % "0.0.2"</code><br/>
      <code>"com.github.dnvriend" % "akka-persistence-inmemory_2.11" % "0.0.2"</code>
    </td>
  </tr>
  </table>
  
  Published to Maven Central. Compliant with <code>akka-persistence-testkit 0.3.4</code>.

* **[JDBC plugin](https://github.com/dnvriend/akka-persistence-jdbc)** (by [Dennis Vriend](https://github.com/dnvriend))

  <table class="stats">
  <tr><td>Since Akka version:</td><td>2.3.2</td></tr>
  <tr><td>Latest Akka version:</td><td>2.3.6</td></tr>
  <tr>
    <td>Latest Release:</td>
    <td>
      <code>"com.github.dnvriend" % "akka-persistence-jdbc_2.10" % "1.0.5"</code><br/>
      <code>"com.github.dnvriend" % "akka-persistence-jdbc_2.11" % "1.0.5"</code>
    </td>
  </tr>
  </table>

  Published to Maven Central. Compliant with <code>akka-persistence-testkit 0.3.4</code>.

* **[MySQL & PostgreSQL plugin](https://github.com/okumin/akka-persistence-sql-async)** (by [okumin](https://github.com/okumin))

  <table class="stats">
    <tr><td>Since Akka version:</td><td>2.3.6</td></tr>
    <tr><td>Latest Akka version:</td><td>2.3.6</td></tr>
    <tr><td>Latest Release:</td><td><code>"com.okumin" %% "akka-persistence-sql-async" % "0.1"</code> (Sep 30, 2014)</td></tr>
  </table>

  Published to Maven Central. Compliant with [`akka-persistence-tck`](http://doc.akka.io/docs/akka/2.3.6/scala/persistence.html#plugin-tck).

* **[Shared In-Memory Plugin](https://github.com/jdgoldie/akka-persistence-shared-inmemory/)** (by [Joshua Goldie](https://github.com/jdgoldie))

  <table class="stats">
  <tr><td>Since Akka version:</td><td>2.3.6</td></tr>
  <tr><td>Latest Akka version:</td><td>2.3.6</td></tr>
  <tr><td>Latest Release:</td><td><code>"com.github.jdgoldie" % "akka-persistence-shared-inmemory_2.10" % "1.0.15"</code><br><code>"com.github.jdgoldie" % "akka-persistence-shared-inmemory_2.11" % "1.0.15"</code></td></tr>
  </table>

  Published to bintray at the URL `http://dl.bintray.com/jdgoldie/maven`.

  In-memory implementations of the journal and snapshot store designed to work with multi-node and single-node unit tests.  Tested against `akka-persistence-tck-experimental` version 2.3.6

## Projects Using Akka

* **[Play Framework](http://www.playframework.org/)**

  <table class="stats">
  <tr><td>Since Akka version:</td><td>2.0</td></tr>
  <tr><td>Latest Akka version:</td><td>2.2.4</td></tr>
  <tr><td>Latest Release:</td><td>2.2.2 (March 1, 2014)</td></tr>
  </table>

* **[Spray: REST library](http://spray.io)**

  <table class="stats">
  <tr><td>Since Akka version:</td><td>1.0</td></tr>
  <tr><td>Latest Akka version:</td><td>2.3.0</td></tr>
  <tr><td>Latest Release:</td><td>several, check <a href="http://spray.io/project-info/current-versions/">this page</a> for details</td></tr>
  </table>

* **[Spark: Cluster Computing](http://spark-project.org/)**

  <table class="stats">
  <tr><td>Since Akka version:</td><td>unknown</td></tr>
  <tr><td>Latest Akka version:</td><td>unknown</td></tr>
  <tr><td>Latest Release:</td><td>unknown</td></tr>
  </table>

* **[Socko: Web Server](http://sockoweb.org/)**

  <table class="stats">
  <tr><td>Since Akka version:</td><td>unknown</td></tr>
  <tr><td>Latest Akka version:</td><td>unknown</td></tr>
  <tr><td>Latest Release:</td><td>unknown</td></tr>
  </table>

* **[Scalatra: Web Framework](http://www.scalatra.org/)**

  <table class="stats">
  <tr><td>Since Akka version:</td><td>unknown</td></tr>
  <tr><td>Latest Akka version:</td><td>unknown</td></tr>
  <tr><td>Latest Release:</td><td>unknown</td></tr>
  </table>

* **[GeoTrellis: Geoprocessing Engine](http://www.azavea.com/products/geotrellis/)**

  <table class="stats">
  <tr><td>Since Akka version:</td><td>unknown</td></tr>
  <tr><td>Latest Akka version:</td><td>unknown</td></tr>
  <tr><td>Latest Release:</td><td>unknown</td></tr>
  </table>

* **[Gatling: Stress Test Tool](http://gatling-tool.org/)**

  <table class="stats">
  <tr><td>Since Akka version:</td><td>unknown</td></tr>
  <tr><td>Latest Akka version:</td><td>unknown</td></tr>
  <tr><td>Latest Release:</td><td>unknown</td></tr>
  </table>

* **[Raiku: Riak client](https://github.com/gideondk/Raiku)** (by [Gideon de Kok](https://github.com/gideondk))

  <table class="stats">
    <tr><td>Since Akka version:</td><td>n/a</td></tr>
    <tr><td>Latest Akka version:</td><td>2.2.0</td></tr>
    <tr><td>Latest Release:</td><td><code>"nl.gideondk" %% "raiku" % "0.6.1"</code> (December 23, 2013)</td></tr>
  </table>

  Published to: `https://raw.github.com/gideondk/gideondk-mvn-repo/master`

* **[Riak Scala Client](http://riak.scalapenos.com/index.html)**

  <table class="stats">
  <tr><td>Since Akka version:</td><td>unknown</td></tr>
  <tr><td>Latest Akka version:</td><td>unknown</td></tr>
  <tr><td>Latest Release:</td><td>unknown</td></tr>
  </table>

* **[Redis Scala Client](https://github.com/debasishg/scala-redis-nb)**

  <table class="stats">
  <tr><td>Since Akka version:</td><td>unknown</td></tr>
  <tr><td>Latest Akka version:</td><td>unknown</td></tr>
  <tr><td>Latest Release:</td><td>unknown</td></tr>
  </table>

* **[Brando: Redis Client](https://github.com/chrisdinn/brando)**

  <table class="stats">
  <tr><td>Since Akka version:</td><td>unknown</td></tr>
  <tr><td>Latest Akka version:</td><td>unknown</td></tr>
  <tr><td>Latest Release:</td><td>unknown</td></tr>
  </table>

* **[rediscala: Redis Client](https://github.com/etaty/rediscala)**

  <table class="stats">
  <tr><td>Since Akka version:</td><td>unknown</td></tr>
  <tr><td>Latest Akka version:</td><td>unknown</td></tr>
  <tr><td>Latest Release:</td><td>unknown</td></tr>
  </table>

* **[elasticmq: message queue with an SQS-compatible interface](https://github.com/adamw/elasticmq)** (by [Adam Warski](https://twitter.com/adamwarski))

  <table class="stats">
  <tr><td>Since Akka version:</td><td>2.1.4</td></tr>
  <tr><td>Latest Akka version:</td><td>2.3.2</td></tr>
  <tr><td>Latest Release:</td><td><code>"org.elasticmq" %% "elasticmq-rest-sqs" % "0.8.0"</code> (April 29, 2014)</td></tr>
  </table>

* **[Kamon: reactive applications monitoring](https://github.com/kamon-io/Kamon)**

  <table class="stats">
  <tr><td>Since Akka version:</td><td>2.2.0</td></tr>
  <tr><td>Latest Akka version:</td><td>2.3.2</td></tr>
  <tr><td>Latest Release:</td><td><code>"io.kamon" %% "kamon-core" % "0.3.2"</code> (July 29, 2014)</td></tr>
  </table>

  Kamon is a set of tools that helps you to get metrics out of your reactive applications. With Kamon you can get actor,
  trace and dispatcher metrics, user defined metrics (histograms, counters, gauges)  and automatic trace recognition for
  Spray and Play! applications. Currently we support NewRelic, Datadog and StatsD as backends for metric data and using
  our simple subscriptions messaging protocol you can get your metrics data anywhere you want. Head over to
  [kamon.io](http://kamon.io) for more information about how to get started with Kamon!

* **[akka-kafka: actor based kafka consumer](https://github.com/sclasen/akka-kafka)**  (by [Scott Clasen](https://github.com/sclasen))

  <table class="stats">
  <tr><td>Since Akka version:</td><td>2.3.2</td></tr>
  <tr><td>Latest Akka version:</td><td>2.3.2</td></tr>
  <tr><td>Latest Release:</td><td><code>"com.sclasen" %% "akka-kafka" % "0.0.2"</code> (April 21, 2014)</td></tr>
  </table>

  akka-kafka is an actor based kafka consumer built on top of the high-level kafka consumer that allows
  for asynchronous/concurrent processing of messages from kafka while keeping an upper bound on the number of
  in-flight messages, and explicitly managing the commit of offsets.

* **[akka-analytics](https://github.com/krasserm/akka-analytics/)** (by [Martin Krasser](https://github.com/krasserm))

  <table class="stats">
  <tr><td>Since Akka version:</td><td>2.3.4</td></tr>
  <tr><td>Latest Akka version:</td><td>2.3.4</td></tr>
  <tr><td>Latest Release:</td><td><code>"com.github.krasserm" % "akka-analytics-cassandra_2.10" % "0.1"</code><br><code>"com.github.krasserm" % "akka-analytics-kafka_2.10" % "0.1"</code></td></tr>
  </table>

  Large-scale event processing with Akka Persistence and Apache Spark.

  Published to bintray at the URL `http://dl.bintray.com/krasserm/maven`.

* **[Project Blended](https://github.com/woq-blended/blended)**

  <table class="stats">
  <tr><td>Since Akka version:</td><td>2.3.2</td></tr>
  <tr><td>Latest Akka version:</td><td>2.3.5</td></tr>
  <tr><td>Latest Release:</td><td>1.0.7-M3</td></tr>
  </table>

  *Project Blended* is a collection of reusable bundles for OSGi development. The latest additions are
  focused on integrating Akka and OSGi to get the best out of the worlds. The first application of the Akka
  integration is to add spray support to an OSGi container. The project is the application core for several
  retail applications. Get started by reading our ideas on [akka and spray integration](http://www.wayofquality.de/projects/blended/)
  into an OSGi container.
  
  We have just added an integration test framework based on Akka, Docker and Scalatest. 

* **[Streamz](https://github.com/krasserm/streamz)** (by [Martin Krasser](https://github.com/krasserm))

  <table class="stats">
  <tr><td>Since Akka version:</td><td>2.3.3</td></tr>
  <tr><td>Latest Akka version:</td><td>2.3.6</td></tr>
  <tr><td>Latest Release:</td><td>0.2</td></tr>
  </table>

  Streamz is a resource combinator library for [scalaz-stream](https://github.com/scalaz/scalaz-stream). It allows ``scalaz.stream.Process`` instances to consume from and produce to

  - [Apache Camel](http://camel.apache.org/) endpoints
  - [Akka Persistence](http://doc.akka.io/docs/akka/2.3.5/scala/persistence.html) journals and snapshot stores and
  - [Akka Stream](http://akka.io/docs/#akka-streams-and-http) flows (reactive streams) with full back-pressure support.

  Published to bintray at the URL `http://dl.bintray.com/krasserm/maven`.

A selected list of some of the projects hosted on GitHub is collected in the
[Akka Actor Corpus](http://actor-applications.cs.illinois.edu/akka.html)
project for the purpose of researching code patterns around this actor model
implementation.
