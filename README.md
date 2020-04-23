# Bo11 Angular Serve



![Docker stats](https://dockeri.co/image/naologic/bo11-serve)

Currently this image uses node 12 (npm 6) and node as base distribution.

## Example usage 

To run the Nest CLI development server from docker you need to map the port.
For example use
```
cd MyDemo
docker run --rm --expose 4200 -p 4200:4200 -v "$PWD":/app naologic/bo11-serve -e "npm_run_command=start"
```
