# Cinnamon-Budgie-Linux-OS-11-based-19.04-Ubuntu-Pop требуется флешка на 8 гигабайт

Update Cinnamon-Budgie-Linux-OS-12-based-19.04-Ubuntu-Pop X64 Android + новое дополненное меню + my skel setting + Android

Скачать VIP дистрибутив Download Cinnamon Budgie OS 12 19.04 iso https://drive.google.com/drive/folders/12ioSo0vCnCfyi577W2MYxiDHVUxTgpeP + (Android https://yadi.sk/d/Cc-bpsnqtk1b9w)

Скачать Download Cinnamon Budgie OS 11 19.04 iso https://dropmefiles.com.ua/SNDxLaTs + (Android https://yadi.sk/d/Cc-bpsnqtk1b9w)

OS 12 19.04 обновлено ни каких записей при загрузке на черном экране типа drm нету ядро новое версии 5.0.0-20 

Последняя версия ядра linux-image-5.2.5 с моим конфигом (это значит вы можете подкинуть мои конфиг и сами скомпилировать) теперь  3G LTE свистки работают сразу после одного моргания диодом https://drive.google.com/open?id=165c-Zuk2j0Dwpypo068fiQ5cUPwbWk_N и ещё одна версия ядра благодаря конфигу maurom ранее на более старом ядре блютус гарнитура воспроизводила рывками тут проверено нету такой задержки как и в ядре выше тоже скачать с гугл диска https://drive.google.com/file/d/1RX8lqrcAzqSKU9HdaZvI3ddiY34Dasil/view?usp=sharing так же в самой ветке maurom следите может новее ядро выйдет https://maurom.com/kernel смотрите какое ядро больше подойдёт вашему оборудованию ну естественно ставим их по очереди удаляя предыдущее так как они имеют одинаковое название иначе рискуете.

Если у вас uefi то тут инструкция впереди создается раздел типа fat32 в gparted флаги ставим efi https://github.com/Griggorii/UEFI_ESP_Linux_Griggorii_instructions_readme из папки ESP без самой папки копируем все фаилы в этот загрузочный раздел потом при установке при uefi она закончится ошибкой , но это ошибкой не будет , а всего лишь предупреждением просто из live не выходим тут же смотрим fstab куда вы установили систему и цифры переписываем как сказано в инструкции.

Chromium браузер цветовая гамма и все такое https://github.com/Griggorii/chromium_swiftshader_super_speed_griggorii_patent_revers в ридми сказано chrome://flags/
Flags особенно srgb это очень сильная вещь просто про это не пишут на телефоне тоже можно сочность так поднять.


Система переведена на QT5CT не трогайте пока что эти настройки они уже настроены и могут упасть в сигфолт так как другие темы не 
особо готовы и щупать их безопасно только в режиме гостя. И то кому это надо для разработчиков пусть правят свои баги и испытывают на vlc , qbittorent, kdenlive. 

Если пропадает язык в окружении budgie то сделать в терминале от рута dpkg-reconfigure keyboard-configuration

Звуковые эффекты PulseEffects https://www.twitch.tv/videos/412938081 так же в моей системе есть PulseAudio Equalizer но в купе 
с PulseEffects он не будет работать так если PulseAudio Equalizer будете использовать то включайте его первым при загрузке , одновременно работать не могут так как потребляют один и тот же источник звука. В моём /etc/skel звук настроен сверх качественно вы можете включать музыкальные видео клипы и потом сравнить с windows это байтокодовые настройки и лежат они в 
home/ваш_профиль_/.config/pulse на счет systemd кто то говорит что разжирнел итд так это geoclue разжирел ищите и наказывайте 
кто его туда напихал и ещё и в зависимость.

Скачать Download Cinnamon Budgie OS 11 19.04 iso https://dropmefiles.com.ua/mkMAD update 06.05.2019
Android cm-x86-14.1-r2.i686.rpm распаковать прямо от рута в корень / и обновить груб после перезагрузки можно загрузиться , документация на рабочем столе читать расскажет как создать data.img
Пароль для установки 123 такой же пароль имеет рут. 
Понадобиться флешка с 4 гигабайтами для того что бы образ влез , 
можно взять флешку и не стирая её закинуть туда образ программой WinSetupFromUSB_1-0 
или программой (unetbootin не помню стирает она данные или нет перед прожигом) , 
точный пример без потери данных на флешке WinSetupFromUSB_1-0 выставив галки 
как на картинке https://imgur.com/a/7NugSRA , потому что не у всех есть флешка лишняя и так этот способ даст избежать лишних затрат на флешки , 
в play market тоже есть утилиты типа DriveDroid и другие с помощью которых можно 
даже с телефона установить по кабелю с ПК и установить образ со смартфона.
Для linux я использую https://unetbootin.github.io/linux_download.html просто делаете бинарник в свойствах
исполняемым и либо запускаете от админа или в терминал в той же папке руню рутирую и закидываю в его окно бинарь 
образ указываю предварительно смонтировав флешечку которая предварительно отформатирована не меньше чем fat32

Установка два способа https://www.youtube.com/watch?v=cs4IJLdpfb8 но, на данный момент только systemback да и быстрее

Flesh card / hdd / usb hdd / sdd / vhd / vhdx minimum size memory 16 gb

Как проверить любой дистрибутив , надо открыть настройки vlc плеера если вылетит значит не годится

Systemback также поможет восстановить систему и отремонтировать grub её и ваши фаилы не пропадут 
если они лежат именно в папке home , только пропадут программы которые установили после , это очень 
удобно на днях я попытался скомпилировать и разработать свой xorg-server в итоге ни клавиатура не 
мышь не работали и с помощью systemback я восстановил систему без всяких переустановок просто подмонтировал 
свой sd раздел в /mnt и включил восстановление системных файлов.

Про интернет соединение без роутера https://www.youtube.com/watch?v=mAUXs3WLuug у вас должно быть там всё на родном языке.
step 3: save правильнее , после step 3 yes ничего не делаем и выходим из терминала.
Потом у меня ниже на панели есть network-manager апплет зайдите щёлкнув на него либо лкм или пкм (потому что я не знаю как ваша мышь работает программно или настроена) изменить соединения и удаляете созданные проводное и Автоматический Ethernet и dsl соединение.

Затем жмёте + и создать из списка выбираете DSL/PPPoE

Соединение DSL 1 , 
предковый интерфейс enp2 , 
