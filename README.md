# Swift.__GB__

*init from ubuntu with docker*
- <a href="https://hub.docker.com/_/swift">imagen oficial de swift en dockerhub</a>
- tener en cuanta cada vez que corramos la imagen `sudo docker start swiftQUKI``sudo docker attach swiftQUKI`
- podemos iniciar rapidamente un proyecto en swift ecribiendo en consola `swift package init`
- `swift build` construimos el proyecto
- pero por alguna razon este proyecto no es ejecutable

*iniciamos un proyecto ejecutable*
- `swift package init --type executable`
- `swift build`
- `swift run`

