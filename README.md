# Image Viewer APK — GitHub Actions Build

## Ye files GitHub pe upload karo aur APK automatic ban jayega!

---

## Folder Structure:
```
image-viewer-apk/
├── .github/
│   └── workflows/
│       └── build.yml      ← GitHub Actions (build magic)
├── www/
│   └── index.html         ← Teri HTML app
├── config.xml             ← Cordova config
├── package.json           ← Dependencies
└── README.md
```

---

## Steps:

1. GitHub pe nayi repo banao (ya existing "Fitness" repo use karo)
2. Sari files drag & drop karo (folder structure same rakho)
3. Push/commit karo
4. **Actions tab** pe jao
5. Build automatically shuru hoga (~10-15 min)
6. Build complete hone ke baad **Artifacts** section me `image-viewer-debug.apk` download karo

---

## APK Install kaise karo phone pe:
- Phone me **Settings → Security → Unknown Sources** ON karo
- APK download karo aur install karo
