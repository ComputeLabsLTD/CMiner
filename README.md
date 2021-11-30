# CMiner
The fastest Cuda Ethereum miner in the market

Welcome! 欢迎你! Приветствую!
------

After an intense development we are proud to finally present you our newest creation: CMiner, a fast and reliable software to mine Ethereum on your Nvidia graphics card. Let us summarize its key features

- It is fast: CMiner can compete with all current competitors in the market and is often superior when it comes to pool side results
- It is easy: The complete configuration only requires few basic parameters
- It is compatible: It is working for every Nvidia card from the Pascal generation and newer. Also it is compatible with every Cuda driver since Cuda 8
- It is safe to use: CMiner does not read or write any data to your hard disk. Additionally the developer fee of 1% is always transferred by using TLS encryption to ensure that the data stream cannot be read by third parties

-------------

经过紧张的开发，我们很自豪地最终向您介绍我们的最新创作。CMiner，一个在你的Nvidia显卡上挖掘以太坊的快速而可靠的软件。让我们总结一下它的主要特点

- 它是快速的。CMiner可以与目前市场上所有的竞争对手竞争，而且在池边结果方面往往更胜一筹。
- 它很容易：完整的配置只需要几个基本参数
- 它是兼容的。它适用于Pascal一代和更新的所有Nvidia显卡。此外，它还与Cuda 8以来的所有Cuda驱动程序兼容。
- 它的使用是安全的。CMiner不会向你的硬盘读取或写入任何数据。此外，1%的开发者费用总是通过使用TLS加密进行传输，以确保数据流不会被第三方读取。

-------------

После интенсивной разработки мы с гордостью представляем вам наше новое творение: CMiner, быстрое и надежное программное обеспечение для добычи Ethereum на вашей видеокарте Nvidia. Давайте подытожим его ключевые особенности

- Быстродействие: CMiner может конкурировать со всеми существующими конкурентами на рынке и часто превосходит их, когда дело доходит до результатов на стороне пула.
- Это легко: для полной настройки требуется всего несколько основных параметров
- Совместимость: CMiner работает со всеми картами Nvidia от поколения Pascal и новее. Также она совместима со всеми драйверами Cuda, начиная с Cuda 8.
- Безопасен в использовании: CMiner не читает и не записывает никаких данных на ваш жесткий диск. Кроме того, плата разработчика в размере 1% всегда передается с использованием TLS-шифрования, чтобы гарантировать, что поток данных не может быть прочитан третьими лицами.

Easy to use! 使用的便利性! Простота в использовании!
------
CMiner 21.12 requires only a small set of mandatory parameters to start its work.  

| **Parameter** | **Description** | 
| ------------- |-------------| 
| --server | The address of the mining pool to connect to. <br />Format: (tls://)server:port |
| --wallet | Your wallet address to mine to |
| --worker | The worker name associated with your mining rig |
| --nicehash | An optional switch to enable the Nicehash stratum protocol |

Example configuration scripts for the most common mining pools are shipped in the distribution package.

-------------

CMiner 21.12只需要一小部分强制性参数就可以开始工作.  
| **参数** | **描述** |
| ------------- |-------------| 
| --server| 要连接的矿池的地址。<br />格式:(tls://)服务器地址 : 端口 |
| --wallet | 你的钱包地址，用于挖矿 |
| --worker |与你的挖矿设备相关的工人名字
| --nicehash |一个可选的开关，以启用Nicehash采矿协议 |

最常见的矿池的配置脚本示例已在发行包中提供。

-------------

Для начала работы CMiner 21.12 требуется лишь небольшой набор обязательных параметров.  
| **Параметр** | **Описание** |
| ------------- |-------------|
| --server| Адрес пула для майнинга, к которому необходимо подключиться. <br />Формат: (tls://)адрес сервера : порт |
| --wallet | Адрес вашего кошелька, на который будет производиться добыча
| --worker | Имя рабочего, связанного с вашей майнинговой установкой |
| --nicehash | Дополнительный переключатель для включения протокола добычи Nicehash |

Примеры сценариев конфигурации для наиболее распространенных майнинговых пулов поставляются в дистрибутиве.
