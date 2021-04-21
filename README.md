
# Ödev:
1. Nginx sunucu çalıştıran ubuntu 18.04 imajı oluşturan bir Dockerfile oluşturacaksınız.
2. GitHub'da kendi hesabınız altında yeni bir docker-study isimli repoya yükleyeceksiniz.
3. Bir README.md dosyası oluşturup hem bu ödevi yazacak hem de Dockerfile'ın nasıl build edileceğini kodlarla bu dosyanın içine yazacaksınız.

# Dockerfile'ı Nasıl Oluşturdum
1. docker pull nginx 
2. docker build -t docker-study
3. docker run --rm -it -p 8080:80 docker-study
