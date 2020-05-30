# -Gartner-CWPP-
本人初学者，欢迎指导&amp;交流


https://www.gartner.com/doc/reprints?id=1-1YSHGBQ8&ct=200416&st=sb?utm_source=marketo&utm_medium=email&utm_campaign=2020-05-22%2003:03:51-Global-DA-EN-20-05-04-7010g000001JNCsAAO-P1-Prisma-2020-gartner-market-guide-for-cwpp-%5BFY20%5D

云原生安全保护的需求不断发展，包括公有云和私有云中的虚拟机、容器、无服务器工作负载，安全管理人员必须解决混合云工作负载环境中独特的安全动态问题。

## 概述
### 问题现状
* 企业使用终端保护平台（EPP）作为服务器工作负载保护，但是EPP 的功能仅仅是用来保护终端用户设施的（如：桌面、笔记本电脑等），这种防护措施无疑将企业的应用程序与数据至于风险之中。
* 大多数企业都使用了不止一个公有云基础设施服务。
* 现在大多数企业都在使用基于容器的服务，并且在尝试PaaS平台服务。
* 对于云远程安全应用，工作负载的安全性需要前置于编码开发过程。
* 现在越来越多的容器和无服务负载被扫描出漏洞，但是对工作负载却很少做保护或者运行时保护措施，而是依靠外部网络检测和事件监视来检测威胁。
* 云工作负载配置不当导致的风险高于工作负载折衷导致的风险。

### Recommendations
为基础设施安全管理人员提供如下几项建议：
* 架构师负责对所有工作负载(无论位置、大小或架构)进行一致的可见性和控制。
* 要求云工作负载保护平台（CWPP）供应商通过计划用于无服务器的解决方案来支持容器。如果您的旧供应商不符合您的容器要求，请公开提出解决方案。
* 将工作负载扫描和合规性工作扩展到开发（DevSecOps），尤其是基于容器和无服务器功能，基于PaaS的开发和部署。
* 要求CWPP产品开放API。
* 在运行时，采用零信任模式来替代以反病毒为中心的策略，At runtime, replace antivirus-centric strategies with a “zero-trust execution”/default deny approach to workload protection where possible, even if used only in detection mode.
* Architect for CWPP scenarios where runtime agents cannot be used or no longer make sense.
* 要求CWPP供应商提供集成云安全态势管理(CSPM)功能，以识别风险配置。

## 市场定义
CWPP的市场由以工作负载为中心的安全产品定义，这些产品针对现代混合，多云数据中心架构中工作负载的独特保护要求（请参阅注2）。 CWPP应为物理计算机，虚拟机（VM），容器和无服务器工作负载提供统一的可见性和控制力，而无论其位置在哪里。
CWPP的产品应该从扫描开发中已知的漏洞开始。在运行时，CWPP产品应该保护工作负载免受攻击，通常包括系统完整性保护、应用程序控制防护、内存保护、行为监视、基于主机的入侵预防和可选的反恶意软件保护功能等。

## 市场描述
终端保护市场已经分化为以终端用户为中心的设备保护产品EPP和CWPP，也就是本文的研究对象。无论工作负载的位置或粒度如何，cwpp都可以保护服务器工作负载免受攻击。cwpp为安全管理人员提供对服务器工作负载的可见性和可控性。然而，现代数据中心的组成、工作负载的粒度和开发速度都在迅速变化。CWPP产品和安全管理人员都必须不断发展，以适应环境的变化。
现代数字业务应用程序和服务由本地和IaaS中运行的多个工作负载组成。在大多数情况下，企业会以定制的方式使用多个供应商的lass服务。尽管使用运行在本地工作负载的情况在减少，但大多数企业认为，至少未来几年内还是会使用本地工作负载的方式。现实情况是，大多数企业将把工作负载分布在本地、托管在多个IaaS服务平台，我们将其称为混合多云架构。 CWPP必须支持这一点。
同时，工作负载的粒度、生命周期以及创建方式也在改变。现在，大多数企业在开发、试验或生产过程中至少使用一个基于Linux容器的应用程序，PaaS服务的采用也越来越多，不管工作负载的粒度如何，都应采用CWPP策略以提供一致的可见性和对工作负载的控制。

图1:工作负载的抽象演化
随着敏捷开发模式盛行，通常每周都会有几次迭代，有时甚至一天好几次迭代，此时工作负载的粒度也变得越来越细化、生命周期也越来越短，保护这些快速变化和短期工作负载的最佳方法是在开发阶段渗入保护机制，以便在生产环节中实例化时，这些工作负载从“诞生”就是受到保护的。此外，云原生应用程序通常虚拟机、容器、以及PaaS服务组成，所有这些设备都需要收到保护。因此，随着工作负载粒度和动态变化，CWPP产品也需要不断适应这一变化。
有时，我们也会发现企业在服务器工作负载上使用了面向终端用户的EPP产品，这些产品是专为台式机、笔记本电脑和平板电脑设计的，它们不适合于动态混合、多云工作负载保护的需求。服务器工作负载面临的风险和威胁明显不同于面向终端用户的系统，使用为终端用户设备设计的EPP产品的企业正在将企业数据和应用程序置于风险之中。相比之下，CWPP专注于现代混合(基于本地和云)、多云(使用多个公共云IaaS供应商)数据中心中服务器工作负载的保护需求。事实上，一些较大的CWPP供应商，如趋势科技(Trend Micro)、赛门铁克(Symantec)和迈克菲(McAfee)，为EPP和CWPP提供不同的、独立的产品，以满足这些市场的独特需求。一些规模较小的厂商只面向CWPP市场。差异包括CWPP的要求，如平台的完全可编程性以及应用程序控制和云平台集成的重要性。CWPP的另一个关键区别是，需要支持在DevSecOps环境中使用持续集成/持续部署(CI/CD)扫描的Linux和Linux容器。

## 市场导向
CWPP为企业提供了一种保护混合、多云工作负载的方法，不管工作负载的位置或粒度，并提供了对所有服务器工作负载的一致可见性和控制。2019年，我们已经正式估计这个市场将达到12.44亿美元，增长率为20.5%，三个最大的供应商——趋势科技、赛门铁克和迈克菲占了CWPP市场年收入的大约一半。
企业越来越多地使用CWPP产品，背后也存在着诸多优势：
* 工作负载正在从本地迁移到公共云IaaS平台, IaaS工作负载的总体数量(包括容器和无服务器功能)正在快速增长。
* 在公共云IaaS平台中，以工作负载为中心、基于主机的CWPP解决方案，提供了比传统基于串联网络的安全策略更易实现的安全架构，拿设备来说，基于工作负载的产品会随着工作负载数量的增加、减少而自动扩展、缩减。
* 在必须终止会话的主机工作负载下，更容易实现对安全套接字层/传输层安全性（SSL / TLS）解密和检查，而不必使用“中间人”方法来解密流量。对于检查基于微服务的体系结构中从一个服务到另一个服务的横向东西向流量，尤其如此。
* 在使用基于容器的应用程序体系结构、基于微服务的应用程序以及采用无服务器PaaS向云原生应用程序开发的转变过程中，CWPP也需要在开发和运行时都具有新的功能。云原生应用程序需要特定的解决方案，这些解决方案旨在满足基于云的系统的保护要求。
CWPP其他关键市场趋势包括：
* 使用云原生加密对公共云中的所有静态数据进行加密。此功能以前是CWPP产品的常见功能，但是大多数企业使用操作系统或底层云结构的内置加密功能（请参阅注释5）。因此，在 2020年市场指南中，加密不是CWPP的必要要求。
* 默认情况下使用基础云平台进行细分。许多企业更喜欢使用基础云结构（例如，Azure网络安全组）的内置分段功能。这减少了CWPP供应商提供基于主机的防火墙的需求。但是，对于那些专注于微细分的CWPP供应商来说，与底层云平台的细分功能的本机功能集成是常见的要求。
* 企业对工作负载威胁检测和响应能力的需求。Gartner在CARTA战略框架和适应性安全架构中指出，CWPP战略不能仅仅依赖于预防性控制。因此，服务器工作负载行为监视(服务器终端检测与响应 EDR)正成为CWPPs的关键需求。像CrowdStrike（以EDR产品闻名）这样的厂商现在正积极地实践工作负载威胁检测和响应。事实上，一些CWPP厂商只关注工作负载的威胁检测/响应(有时也称为云威胁检测和响应 CDR)。
* 工作负载的生命周期越来越短。在使用容器和无服务器计算的云本地开发环境中，影响应用程序的进程和线程很多、变化很快，传统基于加载签名文件和反恶意软件扫描的方式在执行时间上是不允许的。监控运行中的工作负载可能需要数十个实例才能创建可靠的模型。从实例化工作之时起，工作负载就必须“诞生即安全”。这对CI / CD管道中的开发扫描、建模以及仿真都提出了重要要求。
* 向基础架构不变的思维转变。这是一种操作模型，其中不允许在生产系统上进行任何配置更改、补丁程序或软件更新。修补程序和更新将应用在基础（“黄金”）映像和图层，然后从这些映像重新构建生产工作负载并进行替换，而不是提供服务。有了不变的基础架构，CWPP保护策略将在运行时转移到对应用程序控制和容器锁定（默认拒绝/零信任）的关注上，更加着重于在部署之前扫描漏洞。在将工作负载部署到生产中之前，这些策略还将转移到在开发中构建应用程序控制/白名单模型。此概念的一个有趣扩展是内存不变性，它旨在确保在工作负载的生存期内，只有已知的合格代码才能在内存中驻留。
* 在容器环境中，无代理思想的转变。无法保证企业能够在基于容器的部署中将代理放置在Linux主机操作系统中。锁定最小的内核和某些托管容器服务的情况越来越多。答案是提供一种体系结构选项，以将CWPP产品作为特权容器运行，一些CWPP初创公司仅关注容器的保护要求。
* 对Kubernetes的快速适应。在过去的三年中，Kubernetes已经成为Linux容器编排的标准。一些新兴的CWPP厂商只专注于保护Kubernetes环境，支持Amazon Web Services（AWS），Microsoft Azure和Google Cloud Platform（GCP）托管的Kubernetes服务是常见的要求，同时还支持Red Hat OpenShift。
* 转换为CWPP代码分层，包装或插入以保护无服务器功能。在无服务器的PaaS环境中，代理和特权容器/边车将无法工作。需要新的方法，例如在安全控制中分层，4注入安全保护以及创建从安全包装器到无服务器功能的父子关系。一些CWPP初创公司仅关注此用例。
* 无运行时保护。对于容器和无服务器架构，如果在开发中扫描工作负载并满足基本需求(如网络分段)，为什么要在运行时保护中增加对容器/无服务器的负担?假设进行预扫描，则核心运行时保护需求（例如分段，网络监控和行为监控）可能会在工作负载之外交付。随着采用不变的基础架构以及无容器/服务器的PaaS生命周期（以分钟而不是数小时为单位），这种情况越来越多。
* CWPP / CSPM的融合以及云原生应用程序保护平台（CNAPP）的出现。随着对CWPP的安全扫描转换到了开发阶段，扫描云配置是否存在过多风险也是有利的。我们将此风险配置扫描称为云安全状态管理。CSPM是CWPP提供者的自然衔接。


CWPP和CSPM能力的结合具有协同效应，许多厂商都在追求这一战略。这一合并将创建一个新的类别CWPP和CSPM能力的结合具有协同效应，许多厂商都在追求这一战略。这一合并将创建一个新的CNAPPs类别(参见“顶级安全和风险管理趋势”)，用于扫描开发中的工作负载和配置，并在运行时保护工作负载和配置。，用于扫描开发中的工作负载和配置，并在运行时保护工作负载和配置。

## 市场分析
图3显示了现代混合多云数据中心架构中工作负载保护策略的主要元素。

如上图多层次三角形所示，服务器工作负载的安全性源于阴影部分中的基础配置与最佳实践，任何工作负载保护策略都必须从此处开始，并确保满足以下条件：
* 任何人（攻击者或管理员）都无法从物理上或逻辑上访问工作负载。
* 工作负载映像应只具备功能所需代码，服务器镜像应浏览器和电子邮件的使用。
* 对服务器工作负载的更改必须经过严格的管理流程和审核机制，并且通过强制身份认证和访问权限管理（通常使用PAM特权访问管理产品）。
* 操作系统和应用程序日志作为整个企业安全信息和事件管理(SIEM)工作的一部分进行收集和监视。
* 工作负载需要最小化、补丁化和加固，减少攻击面暴露。
* 根据基于身份的策略对工作负载进行细分-在大多数情况下，使用内置的细分功能，例如对部署了云工作负载的基础可编程云基础架构进行标记。
在以上几点的基础上，建议采用服务器工作负载保护金字塔的预防、检测和响应三个组合，它们提供了一个全面的工作负载保护策略。但是，根据工作负载的使用情况、工作负载的暴露程度以及企业的风险承受能力，并不是每个服务器工作负载都严格需要每一层的功能。

### CWPP金字塔的八大组件
CWPP金字塔共有八大组件，最底下的两层涵盖了加固、安全配置、漏洞管理和网络划分，囊括了操作安全和CWPP，是至关重要的两层。

#### CWPP第一层组件：Hardening, Configuration and Vulnerability Management
删除不必要的组件，如Telnet、FTP等其他服务，(如果无法删除，则在管理策略上禁用)。镜像应该使用行业标准指南(如Internet Security Center  CIS指南)作为进行加固，这些特定的步骤可以由IT操作来维护和执行(因此在基础中包含这个层)。确保系统根据组织的指导方针进行加固和配置，并根据组织的政策和行业最佳实践及时更新系统。
在许多情况下，可以使用外部扫描工具或服务（例如Cavirin，Qualys，Rapid7或Tenable）来实现此功能。但是，在本市场指南中的某些CWPP解决方案还可以使用其代理从“由内而外”评估工作负载系统的配置、合规性和漏洞状态，在这种情况下，CWPP应根据工作负载的内容为加强工作负载提供具体的策略建议。

#### CWPP第二层组件：Network Firewalling, Visibility and Microsegmentation   
工作负载安全性的一项关键要求是对工作负载与其他资源进行通信的能力进行防火墙/分段。但是，某些企业不需要CWPP产品即可执行此功能。相反，他们使用云基础结构的内置分段。因此，我们将该层放置在图3中金字塔的阴影矩形部分中。有的CWPP产品提供了自己的防火墙功能，而其他产品则管理Windows和Linux的内置防火墙。一些CWPP还管理Amazon EC2安全组和Microsoft Azure网络安全组的内置分段。一些供应商只专注于微细分。在所有情况下，该解决方案都应满足对基于身份的“微细分”（更细化，软件定义的细分，也称为零信任网络细分的日益增长的需求）数据中心的东西向流量。
此外，一些解决方案还提供了对通信流的可见性和监视，就像某些云服务提供商（例如Azure网络安全组流日志，AWS VPC流日志和GCP防火墙规则日志）一样。为了从原始流日志数据中弄清楚，可视化工具使操作和安全管理员可以了解流模式，设置分段策略并监视偏差。最后，几家供应商提供了工作负载之间网络流量的可选加密（通常是点对点IPsec传输模式安全关联），以保护移动中的数据，并在工作负载之间提供加密网络隔离。

#### CWPP第三层组件：System Integrity Assurance     系统一致性保证
这里的功能在运行时跨越两个领域：
* Preboot
首先，在工作负载实例化期间，在加载其他固件和微代码、hypervisor、vm和容器系统映像之前，测量基本输入/输出系统(BIOS)、统一可扩展固件接口(UEFI)、其他固件和微代码的能力，这通常是通过基于物理系统硬件的信任度量来实现的。在公共云中，这将仅限于在安装和验证地理位置之前测量系统映像和容器的完整性。
* Postboot
实时监视工作负载的完整性，包括工作负载启动后的关键系统文件和配置。与独立防病毒软件一样，单独使用文件完整性监视(FIM)的价值非常小。然而，某些情况下可能需要它，因为FIM是多个法规的要求，比如支付卡行业数据安全标准(PCI DSS)。更高级的解决方案还会监视Windows注册表、启动文件夹、驱动程序、引导加载程序和其他关键系统区域的完整性(请参阅“文件完整性监视的最佳实践”)。比FIM更有用且越来越重要的是监视工作负载配置偏离所需的操作状态。对于不可变的基础设施尤其如此。CWPP提供的一些产品可以监视工作负载，以发现意外的状态变化，并将这些变化重置为所需的设置。

#### WPP第四层组件：Application Control/Whitelisting   应用控制与白名单
本地VM和公共云IaaS中的大多数工作负载都运行单个应用程序。对于托管基于微服务的应用程序和无服务器功能的容器，几乎总是如此。使用应用程序控制来控制服务器上运行的可执行文件提供了非常强大的安全保护策略。这使企业可以对可执行文件采用默认的拒绝或者零信任安全的状态。默认情况下，所有表现为要执行文件的恶意软件都会被阻止。许多CWPP解决方案提供内置的应用程序控制功能，或者提供专门针对此场景的解决方案。
或者，也可以使用的操作系统内置的应用程序控制功能，比如软件限制策略，包括AppLocker和Windows Defender Device Guard、增强性的Linux (SELinux)或使用Linux的AppArmor，或使用VMware的AppDefense。一些厂商可以使用更细粒度的策略对运行时行为做进一步制约。

#### CWPP第五层组件：Exploit Prevention/Memory Protection   利用阻止与内存保护
应用程序控制解决方案是不可靠的，必须结合漏洞利用预防和内存保护功能（例如，地址空间布局随机化（ASLR）和seccomp）结合使用，或与CWPP厂商提供的补充功能结合使用。
我们认为这是一项必不可少的功能，可以防止出现白名单应用程序中的漏洞受到攻击且操作系统受企业控制的情况（对于无服务器，需要保护云服务提供商的底层操作系统）。注入的代码完全从内存运行，并且不会表现为单独执行和可控制的过程（称为“无文件恶意软件”）。此外，漏洞利用防御和内存保护解决方案可以提供广泛的防御攻击的保护，而无需传统的基于签名的防病毒解决方案的开销。当补丁不可用时，它们也可以用作缓解控件。一些CWPP厂商使用了另一种更强大的内存保护方法，称为“移动目标防御”-随机分配OS内核，库和应用程序，以便每个系统在其内存布局上有所不同，以防止基于内存的攻击。

#### CWPP第六层组件：Server Workload EDR, Behavioral Monitoring and Threat Detection/Response
这一层功能也是强制性的。但是，可以通过从工作负载外部进行监视来实现此功能。服务器EDR超越了先前讨论的系统完整性监视（EDR的基本形式），也超越了基于主机的传统入侵检测系统（HIDS）。服务器EDR监视检查行为，例如网络通信，启动的进程，打开的文件以及用于指示恶意活动（包括容器内）的行为模式的日志条目。另一种技术是建立白名单应用程序的预期行为模式，并寻找行为偏差。
一些最终用户EDR点解决方案供应商专门针对服务器工作负载保护用例进行行为监视(请参阅“端点检测和响应解决方案的市场指南”)。这些功能侧重于检测和响应，而不是预防攻击。一些组织将通过基于网络和基于云的监视来实现这一点，而不是使用基于主机的代理(例如，使用主要云提供商的内置网络流日志数据，避免了基于工作负载的持续监视的资源开销)。因此，我们并没有把这作为CWPP的核心要求。服务器EDR的另一个常见用例是，在发生突发事件时，通过名称或散列快速扫描所有系统，寻找特定文件的存在。这类似于基于签名的防病毒扫描，但是如果未使用防病毒引擎，则可用于检测/响应方案。

#### CWPP第七层组件：Host-Based IPS With Vulnerability Shielding
在此，CWPP产品会深度检查传入的网络流量以发现针对已知漏洞的攻击并加以阻止。如果基于网络的入侵防御系统（IPS）保护工作负载，则该层可能是冗余的。但是，基于网络的IPS可能无法抵御VM间或容器间的攻击。另外，由于流量是在主机工作负载处终止的，因此基于主机的入侵防御系统（HIPS）检查可能是更好的体系结构选择，因为它是在主机而不是网络中执行的。 HIPS成为深度控制方面的宝贵防御手段，可防止对零日漏洞的攻击，直到可以应用补丁或从补丁映像重建工作负载的代码为止。一些组织使用HIPS来减少服务器修补的频率。对于保护难以修补的服务器工作负载或供应商不再受修补程序支持的服务器工作负载（例如Windows Server 2008，该服务器工作负载在2019年底不再受支持），它们可能也很关键。

#### CWPP第八层组件：Anti-malware Scanning
基于签名的防病毒和防恶意软件扫描对管理良好的服务器工作负载几乎没有价值。即使服务器工作负载采用了具备内存保护和漏洞利用防御功能的应用程序控制白名单模型，在某些情况下，基于签名的文件扫描很有用。例如，如果服务器工作负载充当通用文件存储库，例如文件共享，网络文件系统（NFS）服务器，FTP服务器或Microsoft SharePoint 服务器等，在这种情况下，应扫描文件存储库。但这可以在CWPP产品之外执行（例如，一些云访问安全代理 CASB 厂商提供此功能）。
存储服务(如公共云IaaS中的对象存储)也应该进行扫描。理想情况下，这些存储服务将取代传统的网络文件共享并移出工作负载。另一个需要防病毒的例外情况是，法规规定强制防病毒软件的使用。可以使用最小的开源软件(OSS)引擎(如ClamAV)进行基本文件系统扫描来满足合规性一种可能的策略；或者，使用您现有的端点防病毒解决方案并对其进行配置，以最小化对服务器性能的影响，例如，可以通过禁用实时扫描、降低计划扫描的频率和将扫描范围缩小到允许更改的文件系统区域来实现这一点。

## 代表厂商
### 市场介绍
 本《市场指南》中列出的代表性供应商（请参阅注释1）在本出版物发行时提供了专门针对在内部和公共云IaaS中服务器工作负载的工作负载保护而设计的运输产品。为了获得对OS本身（如果适用）的详细可见性，使用了代理。对于容器环境，可以使用主机OS代理或特权容器。对于无服务器的工作负载，可以使用分层，包装或注入。
CWPP产品不能只是将在服务器上运行的面向桌面的产品。必须对产品进行设计和优化，以支持企业混合多云架构中本研究中描述的服务器工作负载保护用例。作为托管服务提供的CWPP不在本研究范围之内。必须将基于API的集成到他们正在保护的云架构中。客户端要求的最常见的API集成是VMware，AWS，Azure，OpenStack，Red Hat OpenShift和Kubernetes。
提供以工作负载为中心的防护产品的厂商很多。一些厂商专注于在多个操作系统之间提供尽可能多的防护功能。其他的则专注于微分段、内存保护、行为监视等特定功能，或者仅关注容器或无服务器保护。
为了帮助潜在客户确定哪种CWPP产品最能解决其面临的问题，我们将供应商分为如下八类。
