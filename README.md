# 9anounGPT

## Get started

### Installation:

```shell
git clone https://github.com/mrdaliselmi/9anounGPT.git
cd 9anounGPT
```

### Run locally:

```shell
docker-compose -f docker-compose.prod.yml up
```

### Development:

#### Start developing

```shell
git submodule init
git submodule update --remote --rebase
git submodule foreach --recursive git checkout dev
```
#### Add a submodule

```shell
git submodule add git@github.com:path_to/submodule.git <path-to-submodule>
```
