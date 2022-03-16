# 关于 AliOpenKG：开放的数字商业知识图谱

**描述**：

> 秉承“利用开放的商业知识发现社会经济价值”的理念，阿里巴巴集团发布首个大规模开放数字商业知识图谱AliOpenKG。第一个版本已包含了超过18亿的三元组，多达67万的核心概念，2681类关系，后面还将持续维护与扩展。基于图谱中的商业要素知识，有利于深度理解零售数据，有利于数智驱动商品运营、商家成长，优化市场供需匹配， 产生更多贴近场景需求的智能应用。依托于开放图谱中的行业知识与标准规范，有利于商业生态中各类数据要素的融合与流通，有利于数字商业和经济生态的深入发展，进一步帮助中小企业实现数智化转型。利用开放的商业知识发现社会经济的价值，还可以促进数字商务数字经济等领域的交叉学科研究，服务数字经济健康发展的国家战略需求。

下载链接：https://tianchi.aliyun.com/dataset/dataDetail?dataId=119451


**数据集介绍：**

>商业要素涉及多种不同类型的知识，我们针对不同的知识类型采用不同的知识建模方法。例如针对标品知识所涉及的类目及属性关系型知识，我们采用本体表示语言进行建模；对于概念型知识我们采用更为简单概念层次关系表示方法；对于实体关系型知识我们采用属性图Property Graph方式进行建模；对于商业规则知识我们采用规则知识建模方法。通过建立一套基于消费者需求场景的知识图谱表示体系来组织商品，并把商业要素知识沉淀到图谱中，以解决业务痛点。AliOpenKG已经包含近200万元组的本体三元组，一百多万条概念知识，近十多亿的实体关系三元组，以及二十多万条的规则型知识（待发布）。下图是一个案例，展示了AliOpenKG的数据组织形式。



**格式/协议：**

>数据分为TBox、ABox和sample_data三部分，支持.ttl、.nt、.jsonld、.owl四种数据格式。
>其中，i）.ttl、.owl格式: 与 .xml 格式类似；ii）.nt: 三元组格式，每一行的数据格式为[头实体]\t[关系]\t[尾实体]；iii）.jsonld 与 .json格式类似。



**数据集统计信息:**

>| 类及属性个数 | 46万+   |
>| ------------ | ------- |
>| 核心概念书   | 67万+   |
>| 标准产品数   | 306万+  |
>| 总实体数     | 1600万+ |
>| 总三元组数   | 18亿+   |



**文件清单:**

> **1.AliOpenKG_ABox_Part1.zip:**
>
> AliOpenKG_ABox_Product_OriginStr_Attributes.nt.tar.gz 
>
> AliOpenKG_ABox_Product_OriginStr_Attributes.ttl.tar.gz
>
> AliOpenKG_ABox_Product_OriginStr_wClass.nt  
>
> AliOpenKG_ABox_Product_OriginStr_wClass.ttl
>
> **2.AliOpenKG_ABox_Part2.zip:**
>
> AliOpenKG_ABox_Product_OriginStr_wConcept_marketOnly_part1.ttl.tar.gz
>
> AliOpenKG_ABox_Product_OriginStr_wConcept_marketOnly_part2.ttl.tar.gz
>
> AliOpenKG_ABox_Product_OriginStr_wConcept_marketOnly_part3.ttl.tar.gz
>
> AliOpenKG_ABox_Product_OriginStr_wConcept_marketOnly_part4.ttl.tar.gz
>
> **3.AliOpenKG_ABox_Part3.zip:**
>
> AliOpenKG_ABox_Product_OriginStr_wConcept_marketOnly_part5.ttl.tar.gz
>
> AliOpenKG_ABox_Product_OriginStr_wConcept_marketOnly_part6.ttl.tar.gz
>
> AliOpenKG_ABox_Product_OriginStr_wConcept_marketOnly_part7.ttl.tar.gz
>
> AliOpenKG_ABox_Product_OriginStr_wConcept_marketOnly_part8.ttl.tar.gz
>
> **4.AliOpenKG_ABox_Part4.zip:**
>
> AliOpenKG_ABox_Product_OriginStr_wConcept_marketOnly_part9.ttl.tar.gz
>
> AliOpenKG_ABox_Product_OriginStr_wConcept_marketOnly_part10.ttl.tar.gz
>
> AliOpenKG_ABox_Product_OriginStr_wConcept_marketOnly_part11.ttl.tar.gz
>
> AliOpenKG_ABox_Product_OriginStr_wConcept_marketOnly_part12.ttl.tar.gz
>
> **5.AliOpenKG_ABox_Part5.zip:**
>
> AliOpenKG_ABox_Product_OriginStr_wConcept_marketOnly_part13.ttl.tar.gz
>
> AliOpenKG_ABox_Product_OriginStr_wConcept_marketOnly_part14.ttl.tar.gz
>
> AliOpenKG_ABox_Product_OriginStr_wConcept_marketOnly_part15.ttl.tar.gz
>
> AliOpenKG_ABox_Product_OriginStr_wConcept_marketOnly_part16.ttl.tar.gz
>
> **6.AliOpenKG_ABox_Part6.zip:**
>
> AliOpenKG_ABox_Product_OriginStr_wConcept_marketOnly_part17.ttl.tar.gz
>
> AliOpenKG_ABox_Product_OriginStr_wConcept_marketOnly_part18.ttl.tar.gz
>
> AliOpenKG_ABox_Product_OriginStr_wConcept_marketOnly_part19.ttl.tar.gz
>
> AliOpenKG_ABox_Product_OriginStr_wConcept_marketOnly_part20.ttl.tar.gz
>
> **7.AliOpenKG_ABox_Part7.zip:**
>
> AliOpenKG_ABox_Product_OriginStr_wConcept_part1.nt.tar.gz  
>
> AliOpenKG_ABox_Product_OriginStr_wConcept_part1.ttl.tar.gz 
>
> AliOpenKG_ABox_Product_OriginStr_wConcept_part2.nt.tar.gz  
>
> AliOpenKG_ABox_Product_OriginStr_wConcept_part2.ttl.tar.gz  
>
> AliOpenKG_ABox_Product_OriginStr_wConcept_part3.nt.tar.gz  
>
> AliOpenKG_ABox_Product_OriginStr_wConcept_part3.ttl.tar.gz
>
> AliOpenKG_ABox_Product_OriginStr_wConcept_part4.nt.tar.gz  
>
> AliOpenKG_ABox_Product_OriginStr_wConcept_part4.ttl.tar.gz  
>
> AliOpenKG_ABox_Product_OriginStr_wConcept_part5.nt.tar.gz  
>
> AliOpenKG_ABox_Product_OriginStr_wConcept_part5.ttl.tar.gz
>
> **8.AliOpenKG_ABox_Part8.zip:**
>
> AliOpenKG_ABox_Product_OriginStr_wConcept_part6.nt.tar.gz
>
> AliOpenKG_ABox_Product_OriginStr_wConcept_part6.ttl.tar.gz
>
> AliOpenKG_ABox_Product_OriginStr_wConcept_part7.nt.tar.gz  
>
> AliOpenKG_ABox_Product_OriginStr_wConcept_part7.ttl.tar.gz  
>
> AliOpenKG_ABox_Product_OriginStr_wConcept_part8.nt.tar.gz  
>
> AliOpenKG_ABox_Product_OriginStr_wConcept_part8.ttl.tar.gz  
>
> AliOpenKG_ABox_Product_OriginStr_wConcept_part9.nt.tar.gz  
>
> AliOpenKG_ABox_Product_OriginStr_wConcept_part9.ttl.tar.gz
>
> **9.AliOpenKG_TBox.zip:**
>
> AliOpenKG_TBox_All_OriginStr.jsonld  
>
> AliOpenKG_TBox_All_OriginStr.nt
>
> AliOpenKG_TBox_All_OriginStr.ttl
>
> **10.sample_data.zip**



**文件说明:**

| 文件类型                                                     | 文件内容                                                     |
| :----------------------------------------------------------- | :----------------------------------------------------------- |
| AliOpenKG_ABox_Product_OriginStr_Attributes.[nt\|tl]         | 主要包含产品属性信息                                         |
| AliOpenKG_ABox_Product_OriginStr_wClass.[nt\|ttl]            | 主要包含产品和类别信息，以及与产地、品牌的关联信息           |
| AliOpenKG_ABox_Product_OriginStr_wConcept_marketOnly_part[1-20].ttl | 主要包含产品与5类概念（场景、人群、适用时间、主题、细分市场）实例的联系 |
| AliOpenKG_ABox_Product_OriginStr_wConcept_part[1-9].[nt\|ttl] | 主要包含产品与细分市场这一概念的实例的联系                   |



**数据格式：**Turtle 和 N-triples

1.N-triples

> 例子：AliOpenKG_ABox_Product_OriginStr_Attributes.nt

```
<http://ali.openkg.cn/alischema#Product/pid_ebeca1281d72acc73cc51f0a9e3c5d0e> <http://ali.openkg.cn/alischema#Property/Packaging_Way> "Package" .
<http://ali.openkg.cn/alischema#Product/pid_ebeca1281d72acc73cc51f0a9e3c5d0e> <http://ali.openkg.cn/alischema#Property/Imported> "否" .
<http://ali.openkg.cn/alischema#Product/pid_ebeca1281d72acc73cc51f0a9e3c5d0e> <http://ali.openkg.cn/alischema#Property/Specification> "黑豆" .
<http://ali.openkg.cn/alischema#Product/pid_ebeca1281d72acc73cc51f0a9e3c5d0e> <http://ali.openkg.cn/alischema#Property/品牌归属地> "中国香港" .
<http://ali.openkg.cn/alischema#Product/pid_ebeca1281d72acc73cc51f0a9e3c5d0e> <http://ali.openkg.cn/alischema#Property/Flavor> "Original Flavor" .
<http://ali.openkg.cn/alischema#Product/pid_ebeca1281d72acc73cc51f0a9e3c5d0e> <http://ali.openkg.cn/alischema#Property/品牌类型> "港台品牌" .
```

> 例子：AliOpenKG_ABox_Product_OriginStr_wClass.nt

```
<http://ali.openkg.cn/alischema#Brand/M＆G/晨光_instance1740043> <http://www.w3.org/1999/02/22-rdf-syntax-ns#type> <http://ali.openkg.cn/alischema#Brand/M＆G/晨光> .
<http://ali.openkg.cn/alischema#Product/pid_e7712d3bec6ddedc11d520c67719f156> <http://www.w3.org/1999/02/22-rdf-syntax-ns#type> <http://ali.openkg.cn/alischema#Category/lc_026cafad3935d1db3a696ae72f3bf853> .
<http://ali.openkg.cn/alischema#Product/pid_c4d9ef7fe6a084bd53470a5079c066d8> <http://www.w3.org/1999/02/22-rdf-syntax-ns#type> <http://ali.openkg.cn/alischema#Category/lc_0346cd4ec0bdb648333c73863d25c940> .
<http://ali.openkg.cn/alischema#Brand/趁早_instance1508364> <http://www.w3.org/2000/01/rdf-schema#label> "趁早" .
```

*ps:每条记录是一个主谓宾结构的三元组，用空格隔开，用“.”表示结尾，表示资源的用<>表示。*



2.Turtle

> 例子：AliOpenKG_ABox_Product_OriginStr_wConcept_part[1-9].ttl

```
<http://ali.openkg.cn/alischema#Scene/tag_e4158431091eae8defd5da543937677e_instance5432064>
        a       <http://ali.openkg.cn/alischema#Scene/tag_e4158431091eae8defd5da543937677e> .

<http://ali.openkg.cn/alischema#Product/pid_c4d9ef7fe6a084bd53470a5079c066d8>
        <http://ali.openkg.cn/alischema#Property/forCrowd>
                <http://ali.openkg.cn/alischema#Crowd/tag_12cdb37124998aa21aaa4e6d93a1713b_instance7820492> ;
        <http://ali.openkg.cn/alischema#Property/inMarket>
                <http://ali.openkg.cn/alischema#Market_segment/tag_2af41687d9cef1b184f77f2ab48583d8_instance7820494> , <http://ali.openkg.cn/alischema#Market_segment/tag_d62d73832dad8ab0ceaef141fde9c823_instance7820504> , <http://ali.openkg.cn/alischema#Market_segment/tag_f3089a3c64de1c5c9ebb1aecddecfe27_instance7820497> , <http://ali.openkg.cn/alischema#Market_segment/tag_86154ff52388a394ea28c434e2e0f3de_instance7820498> , <http://ali.openkg.cn/alischema#Market_segment/tag_1325e782ac7f03710bc63efaf4e15812_instance7820491> , <http://ali.openkg.cn/alischema#Market_segment/tag_388da126047442e9ec500b5e16e3f828_instance7820499> , <http://ali.openkg.cn/alischema#Market_segment/tag_ce48d93685eae6a53b26cd80ad2564bb_instance7820489> , <http://ali.openkg.cn/alischema#Market_segment/tag_e7803cc4433400f376c6949061486505_instance7820496> , <http://ali.openkg.cn/alischema#Market_segment/tag_8854aedb623b49535d338f95e01c67f4_instance7820493> , <http://ali.openkg.cn/alischema#Market_segment/tag_87b0bc6f6d46cdfb2e20dc1f63e96554_instance7820495> , <http://ali.openkg.cn/alischema#Market_segment/tag_58a7fd0d0263783cef597a743976963d_instance7820490> , <http://ali.openkg.cn/alischema#Market_segment/tag_ef42ccdc3acad15dff4fa6a9591d3f75_instance7820503> , <http://ali.openkg.cn/alischema#Market_segment/tag_7d701a1e92eaa84aa6ae0806646cc95c_instance7820507> , <http://ali.openkg.cn/alischema#Market_segment/tag_9bb2198b7b02ea3cdb87b0b3834072bd_instance7820508> , <http://ali.openkg.cn/alischema#Market_segment/tag_bc4cedfc5a9c2606a2f724397affd783_instance7820505> , <http://ali.openkg.cn/alischema#Market_segment/tag_568dee8b12cd4bb609b6725c6859ade2_instance7820500> , <http://ali.openkg.cn/alischema#Market_segment/tag_84c4a1142f4826c13ff4e648f311bae2_instance7820501> , <http://ali.openkg.cn/alischema#Market_segment/tag_4df53248bee370f09636fcf679aba9a2_instance7820506> , <http://ali.openkg.cn/alischema#Market_segment/tag_52a525b4806c6dc2db764be8dd1d2106_instance7820502> .
<http://ali.openkg.cn/alischema#Product/pid_a60caeab0de4473c7448d9e680778690>
        <http://ali.openkg.cn/alischema#Property/forCrowd>
                <http://ali.openkg.cn/alischema#Crowd/tag_130601f7d0966eed495fb097545fa836_instance4586767> ;
        <http://ali.openkg.cn/alischema#Property/inMarket>
                <http://ali.openkg.cn/alischema#Market_segment/tag_030008604aebd31847e2806ef2482253_instance4586770> , <http://ali.openkg.cn/alischema#Market_segment/tag_194b773ff31da47d7b0558e17c51926b_instance4586768> ;
        <http://ali.openkg.cn/alischema#Property/relatedScene>
                <http://ali.openkg.cn/alischema#Scene/tag_5c8a96352d35a340e87f5b81ad28d0a5_instance4586769> , <http://ali.openkg.cn/alischema#Scene/tag_f82eeac60ea85cde26df3db7e3be804f_instance4586766> .

<http://ali.openkg.cn/alischema#Market_segment/tag_0e21f9fc46aef6b023c60d9521269760_instance3992200>
        a       <http://ali.openkg.cn/alischema#Market_segment/tag_0e21f9fc46aef6b023c60d9521269760> .
```

> 例子：AliOpenKG_ABox_Product_OriginStr_wConcept_marketOnly_part[1-20].ttl

```
<http://ali.openkg.cn/alischema#Product/pid_b35e74bd4cb7b362bc39b6a2fe29c5b1>
        <http://ali.openkg.cn/alischema#Property/其他元素>
                <http://ali.openkg.cn/alischema#Market_segment/tag_345b0600b00b7694e2c65ebc5d16bd37_instance2325> ;
        <http://ali.openkg.cn/alischema#Property/品类>
                <http://ali.openkg.cn/alischema#Market_segment/tag_05bf77358be13e53a75729570285dadf_instance11335> , <http://ali.openkg.cn/alischema#Market_segment/tag_29a884ce45330660d2e7d686c63c4532_instance3650> ;
        <http://ali.openkg.cn/alischema#Property/图案>
                <http://ali.openkg.cn/alischema#Market_segment/tag_2638e72062121acfef52bd97f7fee154_instance14684> ;
        <http://ali.openkg.cn/alischema#Property/尺码>
                <http://ali.openkg.cn/alischema#Market_segment/tag_cf6d0f31707037905195597161dc0ff8_instance8789> ;
        <http://ali.openkg.cn/alischema#Property/材质>
                <http://ali.openkg.cn/alischema#Market_segment/tag_f96f1f46623092e89261a23183172908_instance14319> ;
        <http://ali.openkg.cn/alischema#Property/版型>
                <http://ali.openkg.cn/alischema#Market_segment/tag_4e232e04ec7934c313ebb99fc7a30147_instance11010> ;
        <http://ali.openkg.cn/alischema#Property/衣长>
                <http://ali.openkg.cn/alischema#Market_segment/tag_c1aa37eefb74c29dc908039c55969108_instance14253> ;
        <http://ali.openkg.cn/alischema#Property/袖长>
                <http://ali.openkg.cn/alischema#Market_segment/tag_e2574b87f003f9264ac02e9829013404_instance13626> ;
        <http://ali.openkg.cn/alischema#Property/设计细节>
                <http://ali.openkg.cn/alischema#Market_segment/tag_b589e0976ffd302aab715cbad65f6b10_instance15088> , <http://ali.openkg.cn/alischema#Market_segment/tag_5c1f9e23f1167e7a6c7ac482be47f393_instance10158> , <http://ali.openkg.cn/alischema#Market_segment/tag_f4e1eb360e010edca7f3566701d09c75_instance15110> , <http://ali.openkg.cn/alischema#Market_segment/tag_d9393a1cbd1aface5710d3bffdf82273_instance10969> ;
        <http://ali.openkg.cn/alischema#Property/适用对象>
                <http://ali.openkg.cn/alischema#Market_segment/tag_9b2c7bd96949f2f8256584116ee478ae_instance16741> ;
        <http://ali.openkg.cn/alischema#Property/面料>
                <http://ali.openkg.cn/alischema#Market_segment/tag_4996a09e59e0adc5476bea1383a854e8_instance5596> , <http://ali.openkg.cn/alischema#Market_segment/tag_89599a054cba26f0596be4f906534931_instance17519> ;
        <http://ali.openkg.cn/alischema#Property/领型>
                <http://ali.openkg.cn/alischema#Market_segment/tag_99ec7b1e00b72c329ebf45691f84ea2f_instance2864> ;
        <http://ali.openkg.cn/alischema#Property/颜色>
                <http://ali.openkg.cn/alischema#Market_segment/tag_344e92f707acc1aa9d1d19180c514ff3_instance18667> , <http://ali.openkg.cn/alischema#Market_segment/tag_ffef79a8e34792f2fe572528c59595e9_instance12133> , <http://ali.openkg.cn/alischema#Market_segment/tag_8f72ac69c1d5d1e4b9de643bf461b919_instance13679> ;
        <http://ali.openkg.cn/alischema#Property/颜色分类>
                <http://ali.openkg.cn/alischema#Market_segment/tag_034e6b3893fcd619dc63e047cb463a91_instance22> ;
        <http://ali.openkg.cn/alischema#Property/风格>
                <http://ali.openkg.cn/alischema#Market_segment/tag_b9f2f3588c54db9f34f6ecb96d08f138_instance9237> , <http://ali.openkg.cn/alischema#Market_segment/tag_ec295c66715155588a46ba932059ec75_instance16055> .

<http://ali.openkg.cn/alischema#Product/pid_39d007466ddef1030ffe1e030b5ba577>
        <http://ali.openkg.cn/alischema#Property/适用阶段>
                <http://ali.openkg.cn/alischema#Market_segment/tag_510ebb98a844d627c5ccb8575d184458_instance19050> .
```

*ps:1.每条记录以“.”结束。每条记录有一个主语，若干对的谓语-宾语集结构，每对以“；”分割。*

*ps2.自定义命名空间：*

```
@prefix xsd:   <http://www.w3.org/2005/xpath-functions#> .
@prefix alis:  <http://ali.openkg.cn/alischema#> .
@prefix skos:  <http://www.w3.org/2004/02/skos/core#> .
@prefix cns:   <http://cnschema.org/> .
@prefix rdfs:  <http://www.w3.org/2000/01/rdf-schema#> .
@prefix ens:   <http://schema.org/> .
```

*ps3.以下的简写“a”表示为资源指定类型*

```
<http://ali.openkg.cn/alischema#Market_segment/tag_0e21f9fc46aef6b023c60d9521269760_instance3992200>
        a       <http://ali.openkg.cn/alischema#Market_segment/tag_0e21f9fc46aef6b023c60d9521269760> .
```

