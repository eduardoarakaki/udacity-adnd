# udacity-adnd
Programa Nanodegree Android Developer

### Android Developer ND Webcast

https://www.youtube.com/playlist?list=PL75hs21J_9KUIredCkT2XXE9dD0LQsmbK

#### Aula 1

- Instalação Android Studio: https://classroom.udacity.com/courses/ud808/lessons/4216368924/concepts/43072785890923#

https://github.com/udacity/ud851-Sunshine
https://github.com/udacity/ud851-Exercises

- Estatística de instalação do Google Play: https://developer.android.com/about/dashboards/#Platform

- Guia para sol~ução de problemas em HAXM: https://software.intel.com/en-us/blogs/2014/03/14/troubleshooting-intel-haxm

- Executar aplicativos no Android Emulator: https://developer.android.com/studio/run/emulator

- Executar aplicativos em um dispositvo de hardware: https://developer.android.com/studio/run/device

---------------------------------
-Gradle na linha de comando
Você também pode executar tarefas de montagem do Gradle da linha de comando, caso prefira. Para começar, você pode navegar até a raiz da pasta do seu projeto. Nela, você pode executar:

./gradlew tasks
Isso exibirá uma lista completa de tarefas executáveis. Talvez você precise executar o chmod +x no gradlew antes de executá-las. Veja este link para instruções mais detalhadas.

link: https://developer.android.com/studio/build/#buildCmd
--------------------------------------------------------------
-Android Debug Bridge
Outra ferramenta que Dan menciona é a adb, que é a abreviação de Android Debug Bridge. A ADB é uma utilidade da linha de comando incluída no SDK do Android. Você não precisa utilizar a adb neste curso, mas, caso goste de usar a linha de comando, você pode se informar mais sobre a adb e outras ferramentas da linha de comando. link:https://developer.android.com/studio/command-line/adb?utm_source=udacity&utm_medium=mooc&utm_term=android&utm_content=adb&utm_campaign=training

Ao digitar adb no terminal, você também recebe uma lista útil de tudo o que a adb pode fazer por você:

Por exemplo, para iniciar seu aplicativo Android pela linha de comando, você pode digitar:

adb shell am start -n com.package.name/com.package.name.ActivityName
```bash
adb shell am start -n com.package.name/com.package.name.ActivityName
--------------------------------