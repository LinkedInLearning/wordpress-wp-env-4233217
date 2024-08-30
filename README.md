# WordPress-Entwicklung mit wp-env

Dies ist das Repository für den **LinkedIn Learning** Kurs `WordPress-Entwicklung mit wp-env`. Den gesamten Kurs finden Sie auf [LinkedIn Learning][lil-course-url].

![COURSENAME][lil-thumbnail-url] 
Sie entwickeln für WordPress Themes und Plugins? Dann brauchen Sie eine lokale Entwicklungsumgebung – wie zum Beispiel zum Beispiel wp-env. wp-env ist die einfachste Möglichkeit, für WordPress zu entwickeln: Sie brauchen exakt zwei Zeilen auf der Kommandozeile und schon haben Sie ein lokales WordPress, inklusive Unittests, X-Debug und der WP CLI. Sehen und lernen Sie mit Tom Rose, wie WP-Env  die Entwicklungszeit verkürzt und die Zusammenarbeit vereinfacht.

## Installation
Um die Übungsdateien für diesen Kurs nutzen zu können, haben Sie drei Möglichkeiten:
1. _(einfach)_ Klicken Sie auf den grünen Button "Code" und dann auf "Download ZIP"
2. _(mittel)_ klonen Sie dieses Repo mit ```
git clone https://github.com/LinkedInLearning/docker-esst-2501813.git```
3. _(fortgeschritten)_ forken Sie das Repo und klonen es dann (z.B. mit ssh)

Nachdem Sie die Dateien lokal vorliegen haben, wechseln Sie in der Kommandozeile in das Verzeichnis, und installieren Sie die Abhängigkeiten mit 
```
npm install
```

## Nutzung
Um Ihre lokale Entwicklungsumgebung zu starten, tippen Sie
```
npm run up
```
Beim ersten Mal dauert der Prozess einige Minuten, ab dem zweiten Mal geht es deutlich schneller.
Sobald wp-env vollständig gestartet, können Sie mit Ihrem Browser auf http://localhost:8888 zugreifen.

### Autor

**Thomas Rose**

_Medienpädagoge_

Sehen Sie sich andere Kurse des Autors auf [LinkedIn Learning](https://www.linkedin.com/learning/instructors/thomas-rose) an.

[lil-course-url]: https://www.linkedin.com/learning/wordpress-entwicklung-mit-wp-env
[lil-thumbnail-url]: https://media.licdn.com/dms/image/v2/D4D0DAQGRyTAlcfHnIQ/learning-public-crop_675_1200/learning-public-crop_675_1200/0/1724828106333?e=2147483647&v=beta&t=2dY83_nqrzunXdAd4wnAewHnu_3bJEOO3Fs7biKMTm4
