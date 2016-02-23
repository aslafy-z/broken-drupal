# BROKEN DRUPAL

## REQUIREMENTS

- docker

## BUILD

```sh
sudo docker build -t <mytag>/broken-drupal ./broken-drupal
```

## RUN

```sh
sudo docker run -it -p '8888:80' <mytag>/broken-drupal
```

## EXPLOIT

> You have to change drupal url in the script before using it. 

```sh
php exploit/reset-pass.php
```

