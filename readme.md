README

Intall dependency:
1. Install module say hello dengan go get github.com/yoga-nugroho129/go-say-hello-module

Upgrade dependency:
1. ganti versi di file go.mod sesuai versi yang diinginkan/terbaru
2. command go get

Upgrage dependency yg major upgare:
1. Hapus import module di file go.mod require github.com/yoga-nugroho129/go-say-hello-module v1.1.0
2. command go get dengan target module versi upgrade go get github.com/yoga-nugroho129/go-say-hello-module/v2
3. perbaiki code sesuai module baru