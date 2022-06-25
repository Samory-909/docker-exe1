# docker-exe1
#Commander à executer#
`shell`
docker run -it -v /MountPoint --name myalpes alpine sh

cd MountPoint && echo "WARNING: ret pointer is null" >> test.py

docker commit myalpine:v12

docker export myalpes > myalpine.tar

cat myalpine.tar | docker import - alpine:v1

docker tag alpine:v1 20032/monalpine

docker push  20032/monalpine
