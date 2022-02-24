
- en la linea 1 nos encontramos con la vercion de swift esto aparentemente auque este comentado es necesario te lo pide cuando copilas
- en la linea 3 vemos que importa un PackageDescription
<a href="https://docs.swift.org/package-manager/PackageDescription/PackageDescription.html">Documentacion PackageDescription</a>
- en la linea 5 vemos que esta pidiendo un nombre ese nombre es el de la carpeta contenedora del package (creo)
- en la linea 15 nos pide el nombre de la carpeta donde esta el ejecutable 
```swift
1// swift-tools-version:5.5
2// The swift-tools-version declares the minimum version of Swift required to build this package.
3        import PackageDescription
4        let package = Package(
5                name: "exe-02",
6                dependencies: [
7// Dependencies declare other packages that this package depends on.
8// .package(url: /* package url */, from: "1.0.0"),
9                ],
10                targets: [
11// Targets are the basic building blocks of a package. A target can define a module or a test suite.
12// Targets can depend on other targets in this package,
13//  and on products in packages this package depends on.
14                .executableTarget(
15                        name: "exe-02",
16                        dependencies: []
17                )]
18        )
```
