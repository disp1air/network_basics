Сети различаются по размерам:
    - маленькие, офисные
    - большие
    - глобальные

кроме того, что существуют различия в размерах сетей, также существуют различия и в используемых технологиях либо протоколах. Т.е. локальные сети(Local Area Network - LAN) используют одни технологии, и эти технологии не работают для глобальных сетей. Соответственно протокол Ethernet который свойственен для маленьких локальных сетей(сотни и тысячи компьютеров) но он не будет работать в глобальных сетях.

Wide Area Network - WAN

Пиринговые сети - в каждый момент времени программа или узел сети одновременно является и клиентом и сервером (пример - торренты). Плюс - нет центрального узла от которого зависят все и следовательно нет единой точки отказа.

Технологии кластеризации - ??? (добавляют избыточность либо резервируют серевера)  

Локальные сети(LAN):
    - покрывают небольную территорию
    - содержат небольшое кол-во узлов
    - используют свои специфические протоколы(эти протоколы обеспечивают достаточно высокую пропускную способность что не возможно в глобальных сетях)

Глобальные сети:
    - представляют собой объединение нескольких локальных сетей
    - покрывают большие территории  

конвергентные сети - тип сети, который одинаково хорошо передает все виды трафика(телефония, видео и пакеты)  

Топология - наглядное представление структуры сети

Способы доставки сообщений:
    - unicast - отправка пакетов между двумя точками(point-to-point)  
    - multicast - у одного источника есть много получателей(много но не все) групповая рассылка  
    - broadcast - широковещательная рассылка - один отправитель пакета - все должны получить данный пакет.  

Шлюз - используется для связи компьютеров одной сети с другой подсетью.

mac-адрес - присваивается сетевому адаптеру(сетевой карте)
ip-адрес - присваивается в рамках ОС

Command Line Utilities  
 - ipconfig (ifconfig for linux)
 - ping - позволяет провести диагностику компьютера в сети - посылается специальный пакет и если сеть работает - возвращается ответ
 - arp - позволяет посмотреть таблицу соответствия mac-адреса и ip-адреса
 - net
 - netstat - показывает сведения о соединениях

Network Hardware  
 - NIC (Network interface controller)- специальное устройство, которое помогает компьютеру подключиться к сети  
 - Repeater - устр-во которое помогает усиливать сигнал  
 - Hub - концентратор - работает на канальном уровне - и в случае передачи данных - все дейтаграммы передаются одновременно на все компьютеры в сети.  
 - Switch - коммутатор - работает на сетевом уровне - и в случае передачи данных - данные передаются только на один определенный компьютер сети. Объединяет компьютеры в сети при помощи топологии "звезда"  
 - Router - маршрутизатор - позволяет соединить две или более компьютерных сети между собой и эти сети могут использовать различный физический тип сети. Также он позволяет выбрать определенный маршрут до определенного компьютера. Содержит таблицу доступности ресурсов сети  

