ПОРЦИЯ 1: проверка компиляции классической Generals под Android

Что внутри (структура папок важна, загружай как есть):
  CMakePresets.json                                    <- заменить существующий
  .github/workflows/build-android-generals.yml         <- новый файл
  Generals/Code/Main/CMakeLists.txt                    <- заменить существующий
  Generals/Code/Main/AndroidCrashHandler.cpp           <- новый файл
  Generals/Code/Main/ReferenceFloatMath.cpp            <- новый файл
