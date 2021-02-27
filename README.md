# Remote-Debugging-with-VS-Code-On-Windows-to-a-ARM-using -NET
 Remote Debugging with VS Code On Windows to a ARM using .NET

[ Удаленная отладка приложения на .NET 5.0 в Visual Studio Code для ARM на примере Banana Pi BPI-M64 и Cubietruck (Armbian, Linux)](http://devdotnet.org/post/udalennaya-otladka-net50-visual-studio-code-dlya-arm-banana-pi-bpi-m64-i-cubietruck-armbian-linux/ " Удаленная отладка приложения на .NET 5.0 в Visual Studio Code для ARM на примере Banana Pi BPI-M64 и Cubietruck (Armbian, Linux)")

Подробное руководство как организовать удаленную отладку разрабатываемого приложения на <a href="https://devdotnet.org/post/chto-novogo-v-net5/">.NET 5.0</a> в Visual Studio Code для устройства на ARM процессоре, на устройстве используется <a href="https://devdotnet.org/post/armbian-linux-distributiv-dlya-otladochnyh-plat-na-arm/">Armbian (Linux)</a>. Благодаря кроссплатформенности .NET 5.0, разработанное приложение будет одинаково работать как в Windows, так и в Linux. Но все становится сложнее, если необходимо взаимодействовать с подсистемами Linux. Каждый раз компилировать в Windows и переносить исполняемые файлы ручным способом на Linux не очень удобно. Один из рабочих примеров для подобного решения является задача отладки взаимодействия приложения на C# в Linux с устройством подключенным по <a href="https://ru.wikipedia.org/wiki/RS-232">протоколу RS232</a>. В качестве платформы запуска будем использовать <a href="https://devdotnet.org/post/otladochnaya-plata-cubietruck/">Cubietruck (ARM32)</a>, и <a href="https://devdotnet.org/post/otladochnaya-plata-banana-pi-bpi-m64/">Banana Pi BPI-M64(ARM64)</a>, работающие на Armbian.

Примеры кода на C# для Visual Studio Code, проекты:

- RemoteAppArm
- RemoteAppArm64