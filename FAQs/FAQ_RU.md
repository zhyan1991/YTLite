# ЧаВо (Часто задаваемые вопросы)

[🇺🇸 English FAQ](FAQ_EN.md) | [✓] 🇷🇺 ЧаВо на Русском

<details>
  <summary>Какие версии iOS поддерживает YouTube Plus?</summary>
  <p>YouTube Plus поддерживает iOS 14 и выше. <strong>Однако</strong>, если вы устанавливаете его сертификатом разработчика, нужно учитывать совместимость самой YouTube с вашей iOS. Вот список последних поддерживаемых версий YouTube для каждой iOS:</p>
  <li><strong>iOS 14</strong>: YouTube v19.20.2</li>
  <li><strong>iOS 15</strong>: YouTube v20.21.6</li>
  <li><strong>iOS 16+</strong>: Любая версия, поддерживаемая YouTube</li>
</details>
<br>
<details>
  <summary>Моя версия iOS более не поддерживается последним YouTube-ом. Что делать?</summary>
  <p>Вот возможные варианты:</p>
  <li><a href="https://ios.cfw.guide/get-started/">Установить джейлбрейк</a>, установить поддерживаемую версию YouTube из App Store, затем <a href="http://dvntm0.github.io/#jb">установить YouTube Plus как твик</a></li>
  <li><a href="https://ios.cfw.guide/installing-trollstore/">Установить TrollStore</a>, установить <a href="https://github.com/Lessica/TrollFools/releases/">TrollFools</a> через TrollStore, установить подходящую версию YouTube из App Store, затем «инжектнуть» <a href="https://github.com/dayanch96/YTLite/releases/">YouTube Plus</a> через TrollFools</li>
  <li>Найти и скачать совместимую IPA-версию в интернете, затем <a href="../README.md#how-to-build-a-youtube-plus-app-using-github-actions">собрать YouTube Plus через GitHub Actions</a></li>
</details>
<br>
<details>
  <summary>Перестала работать функция трансляции на ТВ на сертификате разработчика. Что делать?</summary>
  <p>Пока проблема не будет решена, рекомендуется использовать версию YouTube 20.14.1 или ниже.</p>
</details>
<br>
<details>
  <summary>При попытке воспроизведения видео появляется <strong><em>Произошла ошибка. Обновите страницу и попробуйте снова.</em></strong></summary>
  <p>Прежде чем делать выводы, уточним несколько моментов:</p>
  <ol>
    <li><strong>Это НЕ</strong> из-за блокировщика рекламы</li>
    <li><strong>Это НЕ</strong> потому что ваш аккаунт каким-то образом был помечен</li>
    <li><strong>Это НЕ</strong> из-за того, что ваш аккаунт добавлен в загадочный чёрный список</li>
  </ol>
  <br>
  <p>Проблема, скорее, кроется в самом процессе сайдлоадинга, даже «чистом» YouTube без твиков. <a href="https://github.com/pepeloni-away/userscripts/issues/6#issuecomment-2860641610">Тут</a> пишут, что причина в некорректных или отсутствующих VisitorID/VisitorData. Такая ошибка стала встречаться чаще из-за новых механизмов YouTube по борьбе с загрузчиками.</p>
  <p><strong>Возможные временные решения:</strong></p>
  <ol>
    <li>Полностью выйдите из аккаунта (или всех аккаунтов): <em>Перейдите во вкладку «Вы» → Сменить аккаунт → Управление аккаунтами на этом устройстве → Удалить</em></li>
    <li>Просмотрите несколько длинных видео без входа в аккаунт. Оставайтесь в разлогиненном состоянии несколько часов.</li>
    <li>Заново войдите в аккаунт, на котором возникала проблема</li>
  </ol>
</details>