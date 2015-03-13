# docker-jmeter

Packages JMeter in a docker container

## Example usage

```bash
docker run -i -t --rm -v $(pwd):/root hauptmedia/jmeter bin/jmeter -n -t /root/all_in_one_001.jmx
```
