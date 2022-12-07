---
draft: false 
date: 2022-12-07T21:31:57+08:00
title: "Cara Mengakses Gui Dari Mode CLI Di Ubuntu"
description:
slug: cara-mengakses-gui-di-ubuntu
type : blog
author: ari
tags:
    - Ubuntu
    - Dwm

categories:
    - dwm 

---
Ubuntu merupakan salah satu distro linux yang banyak digunakan dibanding distro linux lainnya. Kemudahan dan tampilan yang menarik menjadi daya tarik para pengguna yang baru pindah dari sistem operasi lainnya.

Ubuntu sendiri sudah menawarkan GUI dan development environment, namun ada beberapa teman-teman yang tidak ingin menggunakan login manager untuk masuk pada tampilan GUI di Ubuntu.

Langsung saja kita mengatur untuk dapat masuk tanpa masuk pada login manager bawaan ubuntu.
- pastikan menghapus gdm, lxdm, atau login manager lainnya yang terinstal.
- Selanjutnya, buat file bernama .xinitrc di /home/user

```shell
touch .xinitrc
```

- setelah itu masukkan perintah dibawah ini di /home/user/.xinitrc seperti di bawah ini:
```shell
dwm
```

- silahkan restart PC kita, lalu masukkan username dan pasword,
- setelah masuk kita ketik startx,
- kita sudah bisa masuk pada GUI ubuntu kita.
