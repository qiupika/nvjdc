更新 nuolanjdc 小贴士：

## 1、停止容器

```
docker stop nolanjdc
```

## 2、定位到nuolanjdc的源码存放路径

#### 例如：群晖：

```
cd /volume1/docker/nolanjdc
```

#### 其他源码存放路径，例如 /root/nolanjdc

```
cd /root/nolanjdc
```

## 3.1、强制更新(适用于修改过源码的情况)

##### 注：群晖使用 git 命令须提前安装好 Git Server 套件，并部署好环境

```
git fetch --all
git reset --hard origin/main
git pull
```

## 3.2、直接更新(适用于未修改过源码的情况)

## 4、启动容器

```
docker start nolanjdc
```

