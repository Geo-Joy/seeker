READ DESCRIPTION  -> <a href="https://github.com/thewhiteh4t/seeker/blob/master/README.md">HERE</a> 

## Usage

### Install docker desktop -> <a href="https://www.docker.com/products/docker-desktop">HERE</a> 
~~~ https://www.docker.com/products/docker-desktop ```

# Docker Usage Any Platform!

#### Step 1
```docker network create ngroknet```

#### Step 2
```docker run --rm -t --net ngroknet --name seeker geojoy/seeker python3 seeker.py -t manual```

#### Step 3
```docker run --rm -t --net ngroknet --name ngrok wernight/ngrok ngrok http seeker:8080```


# Build from scratch:
## Modify - changes images, templates or codebase

``` git clone https://github.com/Geo-Joy/seeker.git```

``` docker build -t geojoy/seeker . ```

#### after build use the commands in Docker usage to start your servers


## Demo

<p align="center">
	<a href="https://www.youtube.com/watch?v=FEyAPjkJFrk"><img src="https://i.imgur.com/48yrleF.png"></a>
</p>
