# Sol2 with CMake and [vcpkg](https://github.com/microsoft/vcpkg)

* Open this project in Visual Studio as "Open as local folder".
* Install `vcpkg` at `C:\vcpkg` (via `git clone https://github.com/microsoft/vcpkg`)
* Run `bootstrap-vcpkg.bat` in the `vcpkg` folder to get `vcpkg.exe`
* Run `vcpkg integrate install` to install `vcpkg` for global usage
* Run `vcpkg install sol2:x64-windows`
* Build/Run the project from within Visual Studio (select the `*.exe` file as startup item)