> [!NOTE]
> This repository is archeived. Please use [Flipbook ROP](https://www.sidefx.com/docs/houdini/nodes/out/flipbook.html).

# houflipbook
![](https://i.gyazo.com/d53b7da48c54f1611b5fd5e7a51ba146.gif)

Houdini native [Flipbook](https://www.sidefx.com/docs/houdini/render/flipbook.html) rendering as workitems via TOP network.

## Requirements
- Python 3.7 interpreter Houdini
- Must be required `ffmpeg` in your system if use `Flipbook OBJ`

## Ops
### Flipbook TOP
![](https://i.gyazo.com/950feea36778f37e0b338167beb7687b.png)

Implemented almost native flipbook settings TOP node. Generated workitems each rendered images.

### Flipbook OBJ
![](https://i.gyazo.com/9f98728347053308986f9e2886db1844.png)

`Flipbook TOP` (TOP network) wrapper OBJ node. Easy to render `.mp4` or `.gif`.


## License
MIT License. see `LICENSE`
