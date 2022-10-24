# Geekbench

<!-- vim-markdown-toc GFM -->

* [參數](#參數)
    - [系統](#系統)
    - [目標](#目標)
* [Geekbench](#geekbench)
    - [binary](#binary)
        + [下載](#下載)
        + [執行](#執行)
    - [apk](#apk)
        + [下載](#下載-1)

<!-- vim-markdown-toc -->

---

## 參數

### 系統

-   Ubuntu 18.04（WSL）

### 目標

-   arm64

## Geekbench

### binary

#### 下載

```zsh
wget https://cdn.geekbench.com/Geekbench-5.4.0-LinuxARMPreview.tar.gz

tar xvfz Geekbench-5.4.0-LinuxARMPreview.tar.gz
```

#### 執行

```zsh
cd Geekbench-5.4.0-LinuxARMPreview

./geekbench_aarch64
```

### apk

#### 下載

-   [Geekbench 4_4.4.2_Apkpure.xapk](https://m.apkpure.com/tw/geekbench-4/com.primatelabs.geekbench/download?from=details)
-   xapk 改成 zip

```zsh
unzip "Geekbench 4_4.4.2_Apkpure.zip"
```
