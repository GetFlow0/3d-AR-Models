# koltuk-modeller

Web sitelerine gömülen 3D/AR koltuk modelleri. jsDelivr CDN ile servis edilir.

## Kullanım (herhangi bir sitede)

```html
<script type="module" src="https://cdn.jsdelivr.net/npm/@google/model-viewer@3.5.0/dist/model-viewer.min.js"></script>
<model-viewer
  src="https://cdn.jsdelivr.net/gh/GetFlow0/3d-AR-Models/models/nova-chester.glb"
  poster="https://cdn.jsdelivr.net/gh/GetFlow0/3d-AR-Models/models/nova-chester-poster.webp"
  ar ar-modes="scene-viewer quick-look" ar-scale="fixed" ar-placement="floor"
  camera-controls camera-orbit="8deg 78deg 4.2m" shadow-intensity="1"
  style="width:100%;height:520px;background:#f2f2f2;border-radius:12px">
</model-viewer>
```

`KULLANICI` → GitHub kullanıcı/organizasyon adı.

- Model listesi + geçmiş: [MODELLER.md](MODELLER.md)
- Her modelin tarihçesi: `gecmis/<ad>.md`
