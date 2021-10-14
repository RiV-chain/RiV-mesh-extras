# RiV-mesh Extras

Generate an iOS framework with:

```
gomobile bind -target ios -tags mobile -o Mesh.framework \
  github.com/RiV-chain/RiV-mesh-extras/src/mobile \
  github.com/RiV-chain/RiV-mesh/src/config
```

Generate an Android AAR bundle with:

```
gomobile bind -target android -tags mobile -o mesh.aar \
  github.com/RiV-chain/RiV-mesh-extras/src/mobile \
  github.com/RiV-chain/RiV-mesh/src/config
```
