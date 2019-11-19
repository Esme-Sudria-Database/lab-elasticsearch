## Motivation

Elasticsearch is a search engine ready to use in your own application.
It is distrubuted, well packaged and API First.

The majority of operations can be done with a Restful HTTP API.

This virtual machine will allow you to test easily Elasticsearch.

## Synopsis

It use vagrant to set up a Virtual Machine on Virtualbox and
uses Ansible to install elasticsearch.

## The latest version

You can find the latest version to ...

    git clone https://github.com/Esme-Sudria-Database/vagrant-elasticsearch.git

## Usage

1 . Query Elasticsearch

```bash
$ curl http://192.168.34.10:9200
{
  "name" : "vagrant",
  "cluster_name" : "docker-cluster",
  "cluster_uuid" : "Ve480hGJSsiutj5_SJZcHg",
  "version" : {
    "number" : "7.4.2",
    "build_flavor" : "default",
    "build_type" : "docker",
    "build_hash" : "2f90bbf7b93631e52bafb59b3b049cb44ec25e96",
    "build_date" : "2019-10-28T20:40:44.881551Z",
    "build_snapshot" : false,
    "lucene_version" : "8.2.0",
    "minimum_wire_compatibility_version" : "6.8.0",
    "minimum_index_compatibility_version" : "6.0.0-beta1"
  },
  "tagline" : "You Know, for Search"
}
```

2 . Use Kibana for data exploration

* go on http://192.168.34.10:5601

## Installation

```bash
$ vagrant up
==> default: Checking if box 'ubuntu/trusty64' is up to date...
==> default: A newer version of the box 'ubuntu/trusty64' is available! You currently
==> default: have version '20160826.0.1'. The latest is version '20161109.0.0'. Run
==> default: `vagrant box update` to update.
==> default: Clearing any previously set forwarded ports...
[...]
==> default: ok: [localhost]
==> default:
==> default: PLAY RECAP *********************************************************************
==> default: localhost                  : ok=23   changed=17    unreachable=0    failed=0
```

## Tests

Describe and show how to run the tests with code examples.

## Contributors

* Fabien Arcellier

## License

A short snippet describing the license (MIT, Apache, etc.)
