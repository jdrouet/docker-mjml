# docker-mjml

Just a wrapping of mjml into a docker image

## Usage

```bash
# build the image
docker build -t myname/mjml .
# use the image
docker run --rm -v $(pwd):/code -w /code myname/mjml mytemplate.mjml -o theresult.html
```
