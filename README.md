# Start Gulp

instalation
-----------

Node js ошибка установки пакета — MSBUILD : error MSB3428: Загрузка компонента Visual C++ «VCBuild.exe» невозможна
Способы решения проблемы указанные в логах ошибки:

1) установка .NET Framework 2.0 SDK,

2) установка Microsoft Visual Studio 2005 или

3) указание адреса компонента в системном пути, если компонент установлен в другом месте.

Но можно проще, надо открыть консоль с правами администратора и:


npm install --global --production windows-build-tools
1
npm install --global --production windows-build-tools
 

$ npm install —save-dev gulp

$ npm install

$ gulp
  
