# 1-4页 简介：AIOps权威指南

随着硬件和软件系统变得更加高效、复杂和有效，与此同时它们也越来越复杂。例如，当虚拟化基础软件取代裸机时，虚拟化为IT团队带来了不得不规划和管理的新的复杂度。近年来往微服务和容器转型的趋势，也同样导致了应用程序组件数量的激增，以及编排所有这些组件所带来的挑战。

传统上，IT Ops团队的能力对于处理如此日益增加的复杂性显得捉襟见肘。要雇用更多员工是成了最直接的对策，但这并不是成本效益较好的解决方案，也无法支持大规模的扩张。

虽然，自动化工具对处理复杂性有一些帮助，但是传统的自动化工具还是需要依赖手工的进行配置、部署和管理，因此，用自动化工具在应对日益复杂的IT环境的方面能力也是有限的。


## 用AIOps来应对复杂性
 
近年来，IT运营人工智能（AIOps）已成为应对IT系统与日俱增的复杂性的更好的解决方案。 AIOps通过大数据、数据分析和机器学习来提供洞察力，并为现代基础设施和软件所需的管理任务提供更高水平的自动化（不依赖于人类操作员）。

因此，AIOps具有巨大的价值。展望未来，AIOps将在IT团队提高效率方面发挥关键作用。它还会使复杂的下一代技术的应用成为可能，而且那些技术的复杂性是传统解决方案无法成功管理的。

简而言之，没有AIOps的帮助，未来的企业将无法生存。如果您的企业尚未开始尝试基于AIOps的解决方案，那么现在就是评估、规划和实施的时候了，AIOps工具应该能够推动业务价值的交付。

本指南旨在给您向AIOps迁移提供帮助。它定义了AIOps，还评估了当前IT行业内AIOps的现状。它还识别并解释了那些AIOps所驱动的核心组件，以及AIOps驱动工具的主要用例。


## 第1章：什么是AIOps？

### 定义AIOps

AIOps即利用机器学习、大数据和自动决策来完成IT任务。AIOps可以自动化那些传统的需要人为的进行大量手工干预的流程。AIOps是“基于算法的IT运营”或“基于人工智能的IT运营”的缩写，于2016年进入IT词典，当时Gartner创造了这一术语，目的是探索如何通过数据分析为IT Ops团队带来新的效率提升。

### 为什么AIOps是创新？

数据分析和机器学习在企业中的应用已经普及了很多年了--它并没有与AIOps一起出现。早在AIOps概念出现之前，IT运营或IT Ops也作为一门独特的学科存在着。

然而，AIOps的创新之处在于，它将基于数据驱动的洞察和IT运营结合在了一起。以前，数据分析主要是应用在提供业务洞察方面，而不是帮助IT运营团队完成工作。

# 5-8页

在某种程度上，数据和机器学习在IT Ops中发挥作用，它们主要受限于基本安全和基础设施监控工具。 IT Ops团队利用自动化工具帮助提高工作效率，但这些工具通常无法根据数据制定复杂的自动化决策，并且需要大量人工工作才能使用。

AIOps通过为IT Ops团队提供访问可通过收集和分析数据来制定高级决策并执行自动化操作的工具来改变这种情况。它代表了一种将数据分析集成到IT Ops中的更精细、更复杂的方法。此外，它还可以帮助传统IT运营管理员过渡到现场可靠性工程师（SRE）角色，并支持符合业务需求的可扩展工作流。


### AIOps现状

虽然没有关于当前AIOps采用率的精确数据，但是Gartner在2017年预测“全球25％的企业将在2019年战略性地实施支持两个或更多主要IT运营职能的AIOps平台”。此外，TechValidate最近研究发现97％的受访IT组织一致认为提供可操作的洞察力的AIOps解决方案将有助于自动化和增强整体IT运营功能。

尽管在大多数企业部署AIOps平台之前可能还需要一段时间，但AIOps已经看到了企业的早期采用。

目前阻碍AIOps采用的主要障碍包括企业对AIOps是否反映真正的创新或仅仅是炒作缺乏确定性。这种怀疑可能会随着越来越多的企业采用AIOps而消失，AIOps的价值变得更加清晰。在2018年NewVantage Partners调查中发现97.2％的高管正在投资建设或启动大数据和人工智能计划。

企业在收集高质量数据方面的信心较低（再加上对如何更好地实施能够提供广泛、长期有价值的AIOps解决方案的不确定性）也阻碍了一些组织采用AIOps。然而，通过充分的研究和规划可以克服这些挑战。


### AIOps结构

这样的计划首先要确定使AIOps成为可能的核心组件，并评估您的业务去有效地实施它们。

AIOps的主要组成部分包括：

* 数据收集。收集数据是启用AIOps的第一步。成功的AIOps和大数据技术用于从不同的来源收集数据，根据需要转换和聚合数据，有效备份和保留数据，并保持有效的维护数据质量，为数据分析和机器学习提供动力。
* 数据分析。一旦数据被适当地收集和转换，就会执行统计分析以从数据中提取见解。
* 机器学习。机器学习是使用从数据分析中收集的见解来做出自动决策的过程。机器学习是通过算法实现的，这些算法允许软件自动对数据显示的信息做出反应。
* 人工智能（AI）。AI指的是更广泛的自动化决策类别，其中机器学习是一个组成部分。

我们下面将在讨论AIOps使用案例和实践的背景下探索的每个组件。


### AIOps使用案例

通过将数据收集、数据分析和机器学习相结合，形成完整的AIOps解决方案，IT Ops团队可以支持以下几个关键使用案例：

* 异常检测。也许AIOps最基本的使用案例是检测数据中的异常，然后根据需要对它们做出反应。
* 原因分析。AIOps还可帮助IT Ops团队自动执行根本原因分析，从而快速解决问题。
* 预测。AIOps允许工具对未来进行自动预测，例如用户流量在给定时间点可能会如何变化，然后做出相应的反应。
* 报警管理。AIOps在帮助IT Ops团队应对他们必须处理的大量警报以支持运营方面发挥着越来越重要的作用。
* 智能修复。AIOps通过自动化工具驱动闭环补救，而不依赖于运维人员。

以下章节将会通过详细解释它们涉及的内容以及如何成功支持它们来深入探讨这些案例。


# 17-20页翻译


Translator: Yuehao (Samuel) Sui

正因此, 多元异常检测提供了更深入、更全面的洞察力。然而, 因为它需要识别多个可进行通用分析的指标, 并建立能够准确解释它们的算法，多元检测也更难有效地实现。并且随着更多指标的引入, 复杂性也在增加，多元检测也更难以扩展。

在大多数情况下, 结合单元和多元检测方法的 AIOps 解决方案可以提供最佳的结果。单元检测可用于基本的警报和监控, 而多元方法可以为更复杂的自动化决策提供能力。

AIOps 解决方案的另一个关键功能是隐藏算法的复杂性。它可以根据所分析的数据类型自动选择正确的算法。

### 检测模型可扩展性

推动 AIOps 的检测过程应该是可扩展的并面向未来的, 而不是仅仅是为了满足一组有限的需求设计的。

可扩展检测策略具有以下特征:

* 添加新指标或将权重修改为检测模型中的各种指标的能力。
* 在检测模型中添加新数据源和技术的能力。
* 随着行为变得更加细致和复杂, 可持续适应动态基线方法。

这实际上意味着检测模型通常是从小规模开始的, 但随着时间的推移, 规模和复杂性都在增加。在一开始, 您的 Aiops 策略可能主要由单元检测模型以及一些基本的多元方法驱动。他们可能会专注于简单的指标, 如内存和磁盘使用情况。但是, 随着时间的推移, 您可能希望通过采用更复杂的多元模式 (如容器的启动时间或无服务器函数的执行时间) 来收集指标, 从而使您的方法更加复杂。

## 第4章: 因果分析


AIOps 的另一个关键用例是因果分析。这指的是通过追踪一个问题至其所有来源, 以帮助解决问题本身的工作。

### 对因果分析的挑战

随着软件环境变得越来越复杂, 并且不同组件之间的依赖关系越来越难以在表面上进行映射, 因此, AIOps 驱动的因果分析变得越来越重要。

想一下, 例如, 有一个由前端组件以及后端数据库组成的 web 应用程序, 将该应用程序作为容器中所承载的一组微服务进行部署。如果 IT 运营团队注意到 web 服务器已开始响应缓慢, 这时若没有基于数据的自动化工具的帮助, 跟踪问题的根本原因可能会是相当困难的。这个问题有可能是由于网络瓶颈引起的。有可能是磁盘故障或数据库配置问题的结果。又或许是容器协调器无法在多个容器实例之间正确地平衡应用程序负载。甚至问题的根源可能是应用程序代码本身。

一个 IT 运营团队可以通过部署自动分析数据的 AIOps 工具, 以确定问题的可能原因, 而不是去手动调查引发问题的每一种潜在的可能性。AIOps 工具可以通过分析网络通信模式、容器的统计信息、应用程序分析器和数据库日志等信息, 快速地使问题可视化。AIOps 工具还提供端到端的可视性, 使 IT 运营团队能够找到他们自己或许从没意识到的问题。

### 因果分析数据采集与情景化

您的因果分析工作是只等效于您所收集的数据的。您必须确定要执行哪些类型的因果分析, 然后确保您正在收集的、标准化的数据是正确无误的, 以支持这些分析。

收集上下文信息和那些与您正在分析的问题没有直接关系的数据也很重要。这包括了过去类似问题所发生的频率和原因, 以及其他系统是否遇到过类似的问题等信息。这样的上下文信息可以帮助您解释问题的范围和意义, 并对其进行相应的优先处理。

### 处理多种原因

有时, 导致问题的原因可能是多方面的。例如, 在上面的 web 应用程序示例中, 网络带宽限制和磁盘 I/O 问题都可能会导致应用程序的响应速度变慢。因此, 你的因果分析策略和反应应该被设计成能够处理“必须要解决多种原因才能解决问题”的情况。


# 21- 25

例如：电商网站在每年的特定时段会遇到业务高峰，预测容量分析可以使电商网站在此时段分配额外的IT资源，同时在其他时段缩减规模以节省成本。
应用性能预警
除软件测试外，AIOps可以在应用程序部署之前发挥作用，帮助优化应用程序性能。例如，预警可以确定应用程序如何响应特定事件。比如DDoS攻击产生了网络流量突增，这时触发预警信息，IT运维团队可以更有效地为该类事件做好准备。
IT运维团队效率提升
预测和趋势识别可以帮助IT运维团队提升自身的能力。例如：在某个时间窗口内事件如何响应？哪类问题导致了最多的事件？通过分析数据来识别趋势，AIOps可以回答这些问题，以便IT运维团队知道在哪里投入更多资源。


## 第6章：智能修复与自动化

AIOps不仅可以帮助IT运维团队识别问题和故障定位，还可以加快故障的修复过程。
快速修复场景
快速修复场景的重要性很容易理解。在日常业务运营中，超过半数的用户会放弃一个加载时间超过3秒的网站，并且页面加载时间延迟1秒，就会导致销售额减少7％。业务部门无法接受由于网站可用性或性能导致的问题，需要快速进行修复。在实时采集和分析的数据的同时，采用AIOps可以迅速深入问题，帮助IT运维团队跟踪问题的原因并提供建议补救措施，以便尽快恢复业务。




利用历史数据进行修复
AIOps还可以帮助IT运维团队快速关联历史数据，发现以前是否出现过类似的问题，快速关联知识库显示出解决方案，从而加快问题解决速度。在没有AIOps的情况下，要通过大量日志和其他数据进行解析和比对两个事件之间的相似性，也不能确定这两个事件是否为问题导致。AIOps的解决方案可以根据历史数据提供准确快速的匹配，以应对这一挑战。
自动化恢复方案
AIOps工具可以在识别问题后采取自动化恢复方案来解决问题。例如，自动化可以阻断主机或端口，以响应安全事件，甚至调用更加复杂的自动化应用程序。
在大部分场景下，自动化恢复方案并不实用，在AIOps提供的解决方案的建议下，采用半自动或是手动实施修复。但随着机器学习算法变得越来越智能，AIOps工具的自动化恢复方案会越来越多，从而实现更快，更无缝的自动化恢复方案。




## 第七章：减少干扰：管理告警

虽然AIOps工具比采用手工工具管理IT基础设施更有效，但也会产生告警疲劳的风险。假如AIOps工具部署或管理不当，它们会生成大量的监控告警，运维工程师会不堪重负并开始忽略告警信息。这个问题通常被称为告警疲劳，会减弱AIOps监控和分析的价值。
为避免告警疲劳并有效管理告警建议采用如下方法：

避免手动设置告警阈值。手动配置为基于固定阈值触发的告警在当今的动态环境中无法正常工作。手动设置告警不仅需要相当长的时间进行配置，而且还会导致误报，因为在某个时刻会同时出现存储，网络或其他资源消耗的告警。AIOps工具可以自动设置阈值，而不是配置手动告警阈值。有些还利用动态基线来配置何时触发告警。

# 29-32

‌图形模型将帮助AIOps工具，在其处理的数据量和复杂性增加的情况下，提供新层次的洞察力。

## 遗传算法

‌随着AIOps的发展，在AIOps应用程序中，遗传算法的使用可能会显着增加。遗传算法是指通过使用数据和机器学习，自动优化自身来改进的软件逻辑。例如，当AIOps算法反复处理某种类型的问题时，它将自动学习哪些解决方案最有效，并训练自己在未来做到那些。

‌遗传算法是AIOps工具实现持续改进能力的重要组成部分。它们不仅可以通过IT Ops工程师减少手动工作来更快地解决问题，而且还可以使AIOps工具本身随着时间的推移变得更快，更准确和更有效，而无需手动更新。



# CA AIOps相关的解决方案

‌自几年前推出以来，CA Technologies一直处于AIOps生态系统的最前沿，并将随着AIOps的发展继续保持领先地位。

‌AIOps功能由CA通过其Digital Experience Insights平台提供，并且包含CA的APM和API监控解决方案的基本部分功能。 CA最近还推出了数字运营智能，这是一种支持AIOps的解决方案，可提供跨域上下文智能，帮助IT运营团队制定更明智，更快的决策，以增强用户体验并提高IT服务质量和性能。它基于开放，功能强大的引擎，通过摄取和分析各种数据集（包括指标，拓扑，文本和日志数据），为用户提供全面的见解。机器学习驱动的分析，以及开箱即用的可视化和关联性，有助于提供卓越的用户体验并提供显著的运营效率。

‌详细了解CA如何在您的AIOps之旅中为您提供指导。


## 关于CA Technologies

‌CA Technologies帮助客户在未来成功，未来从服装到能源的每种商业都在被软件改写。‌从计划到开发到管理到安全，CA公司建立的软件，可以为应用经济中的企业提供转型的燃料。在他们的IT战略的中心使用CA公司的软件，组织能够使用改变我们生活方式的技术，从数据中心到移动设备。‌我们的软件和解决方案帮助我们的客户在新的应用经济中茁壮成长，我们交付部署监控和保证他们的应用和基础设施安全的方法。

## 关于Sweetcode.io

‌Sweetcode.io是由Fixate IO所有和管理的网站。‌它的目标很简单：给技术人员一个共享他们的知识和用高价值的从业者制作的技术内容影响市场的地方。‌Sweetcode承诺发布巧妙设计的内容，支持成熟的开发人员的成长，同时为刚刚开始他们的事业的人作为平台提供服务。‌网站上的所有的内容是从业者制作的，Sweetcode致力于从不知名的开发者获取内容，以给他们一个共享他们的知识的地方。

