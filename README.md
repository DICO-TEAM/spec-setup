# DICO spec setup


## for developer

`tico`
```
sudo docker run --rm dicoteam/dico build-spec --chain=tico --disable-default-bootnode > ticoCustomSpec.json
```

`kico`

```
sudo docker run --rm dicoteam/dico build-spec --chain=kico --disable-default-bootnode > kicoCustomSpec.json
```


## binaries 

```
./dico --collator --chain=./spec/kico.json  -- --execution wasm --chain kusama --port 30334
```