---
draft: false 
date: 2022-11-23T20:57:09+08:00
title: "Text Editor Faforit Saya"
description:
slug: text-editor-faforit-saya
type : blog
author: ari
tags:
    - neovim 

categories:
    - neovim 

---
Pengalaman dan hobi saya menggunakan linux menghantarkan saya dengan yang namanya vim dan neovim. 
Awal mula menggunakan vim maupun neovim membuat saya sangat susah untuk menggunakannya, namun  dengan berjalannya waktu dan mulai terbiasa menggunakan text editor ini membuat saya sangat menikmati menggunakan neovim.

## Instalasi tambahan
1. Lunarvim 
2. konfigurasi di (.local/share/lunarvim/lvim)
3. terminator
4. install lspinstall emmet_ls
5. edit init.lua untuk emmet_ls
    - tambahakan script berikut ini
    - require("lvim.lsp.manager").setup("emmet_ls")
6. plugin 
    - mg979/vim-visual-multi
## shortcut yang sering digunakan
- <space>ld -> untuk diagnostik error
- <space>bf -> untuk mencari file di tab yang terbuka
- <space>f - mencari file dari folder terbuka
- ctrl>
    - h -> untuk pindah tab kiri
    - l -> untuk pindah tab kanan

