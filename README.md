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

## Code Example

```bash
$ curl http://localhost:9200
{
  "name" : "search-1",
  "cluster_name" : "search",
  "cluster_uuid" : "h8Im30o6QLu5yH44er0feA",
  "version" : {
    "number" : "5.0.0",
    "build_hash" : "253032b",
    "build_date" : "2016-10-26T05:11:34.737Z",
    "build_snapshot" : false,
    "lucene_version" : "6.2.0"
  },
  "tagline" : "You Know, for Search"
}
```

You can use [Sense](https://chrome.google.com/webstore/detail/sense-beta/lhjgkmllcaadmopgmanpapmpjgmfcfig?hl=fr) on Google Chrome as extension.

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
==> default: localhost                  : ok=10   changed=0    unreachable=0    failed=0
```

## Tests

Describe and show how to run the tests with code examples.

## Contributors

* Fabien Arcellier

## License

A short snippet describing the license (MIT, Apache, etc.)
