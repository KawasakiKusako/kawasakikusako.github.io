# remote/asset

远程控制静态页（remote/index.html）的素材目录。

- 网关会直接 serve 本目录：`https://<ip>:11414/asset/<file>`
- 页面可通过相对路径引用（如 `asset/logo.svg`）
- 支持：svg / png / jpg / webp / ico / css / js
