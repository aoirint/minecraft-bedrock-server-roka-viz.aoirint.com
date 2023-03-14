# minecraft-bedrock-server-roka-viz.aoirint.com

```shell
git submodule update --init --recursive

docker build -t bedrock-viz ./bedrock-viz

docker run --rm -v "./worlds:/worlds" -v "./public:/public" bedrock-viz --db "/worlds/Bedrock level" --out "/public" --html-most
```

