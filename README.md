## Requirements  
- [Podman](https://podman.io/)  
- [Positron](https://positron.posit.co/) (VScode like IDE)
  
---  
## Build
### Step 1.  
Clone this repository.  
e.g. `git clone https://github.com/hiroakif93/R_podman.git your-project-name`  

### Step 2.  
Modify `Conteinerfile` if necessaly.  
- e.g. when you want to change R version, modify line1 in `Conteinerfile`.  
- Please see [rocker](https://hub.docker.com/_/r-base) which docker image for R.  

### Step 3.


## Troubleshooting

### `ERROR: Cannot connect to the Docker daemon at unix:///Users/<user>/.docker/run/docker.sock`
Switch Docker context back to `default`.
```bash
docker context use default
docker context show
```  