# Command Cheatsheet

## Git

### 状態確認
```bash
git status
```

## Linux / Network

### 現在の場所を確認

```bash
pwd
```

### ファイル一覧を表示

```bash
ls
```

### ディレクトリ移動

```bash
cd ディレクトリ名
```

例：

```bash
cd Documents
```

### 1つ上のディレクトリに戻る

```bash
cd ..
```

### ディレクトリを作成

```bash
mkdir ディレクトリ名
```

例：

```bash
mkdir test
```

### 空ファイルを作成

```bash
touch ファイル名
```

例：

```bash
touch memo.md
```

### IPアドレス確認

```bash
ip a
```

### ルーティング確認

```bash
ip route
```

### 疎通確認

```bash
ping 8.8.8.8
```

### DNS確認

```bash
nslookup google.com
```

### 通信経路確認

```bash
traceroute google.com
```

## メモ

- `pwd` は今いる場所を確認する。
- `ls` は今いる場所にあるファイルやフォルダを見る。
- `cd` はフォルダを移動する。
- `mkdir` はフォルダを作る。
- `touch` は空のファイルを作る。
- `ip a` は自分のIPアドレスを確認する。
- `ip route` は通信経路やデフォルトゲートウェイを確認する。
- `ping` は通信相手に届くか確認する。
- `nslookup` はドメイン名がどのIPアドレスに変換されるか確認する。
- `traceroute` は通信相手までの経路を確認する。