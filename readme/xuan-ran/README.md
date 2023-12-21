---
cover: ../../.gitbook/assets/BeginPlay_Rendering_Schematic.png
coverY: 37.26820388349513
layout:
  cover:
    visible: true
    size: full
  title:
    visible: true
  description:
    visible: true
  tableOfContents:
    visible: true
  outline:
    visible: true
  pagination:
    visible: true
---

# 渲染

<figure><img src="../../.gitbook/assets/BeginPlay_Rendering_Schematic.png" alt=""><figcaption></figcaption></figure>

{% embed url="https://zhuanlan.zhihu.com/p/36675543" %}

{% embed url="https://zhuanlan.zhihu.com/p/264213600" %}

{% embed url="https://zhuanlan.zhihu.com/p/279556619" %}

{% embed url="https://zhuanlan.zhihu.com/p/281351233" %}

{% file src="../../.gitbook/assets/RDG 101_ A Crash Course.pptx" %}

{% embed url="https://docs.unrealengine.com/5.2/zh-CN/render-dependency-graph-in-unreal-engine/" %}

<figure><img src="../../.gitbook/assets/image (2).png" alt=""><figcaption></figcaption></figure>

{% embed url="https://papalqi.cn/ue4renderingdependencygraph/" %}

{% embed url="https://zhuanlan.zhihu.com/p/101149903" %}

{% embed url="https://zhuanlan.zhihu.com/p/36630694" %}

{% embed url="https://zhuanlan.zhihu.com/p/641367884" %}

{% embed url="https://blog.csdn.net/leonwei/article/details/84821849" %}

{% embed url="https://zhuanlan.zhihu.com/p/657669302" %}

{% embed url="https://www.zhihu.com/column/c_1623021177307365376" %}

{% embed url="https://www.zhihu.com/people/tsukip/columns" %}

{% embed url="https://zhuanlan.zhihu.com/p/614758211" %}

{% embed url="https://www.cnblogs.com/timlly/p/14732412.html#431-fscenerenderer" %}

{% hint style="info" %}
至于什么是RDG简单介绍一下吧，在当今游戏渲染流程里面可能会有很多的特性比如SSR，SSAO，Volumetric等等。它们之间的引用关系比如SSAO需要GBuffer的Normal而SSR需要Normal和Microface，而这两个Pass之间又隔了不知道多少个Pass甚至隔了前后帧，这个时候爪动的维护上下层Pass的引用关系和资源的释放就显得无比麻烦，因此RG孕育而生。这个架构思想最初是又寒霜引擎分享的，基本可以理解为一个系统自动管理你每个资源的创建和销毁以及Pass之间的资源引用和复用，以及剔除掉没有连接到FinalColor的Pass，做到不浪费任何一个系统资源从而达到极致的解耦和系统资源占用。
{% endhint %}

{% embed url="https://docs.unrealengine.com/5.3/zh-CN/graphics-programming-overview-for-unreal-engine/" %}

<figure><img src="../../.gitbook/assets/image.png" alt=""><figcaption></figcaption></figure>

{% embed url="https://zhuanlan.zhihu.com/p/508372052" %}

<figure><img src="../../.gitbook/assets/image (1).png" alt=""><figcaption></figcaption></figure>

{% embed url="https://zhuanlan.zhihu.com/p/630717875" %}

{% embed url="https://www.bilibili.com/read/cv18682530/" %}

{% embed url="https://zhuanlan.zhihu.com/p/33865743" %}

{% embed url="https://zhuanlan.zhihu.com/p/612930825" %}

{% embed url="https://www.bilibili.com/video/BV1yb411c7in/?spm_id_from=333.999.0.0&vd_source=f6f10dd471e4def1b221dadd178c9730" %}

{% embed url="https://www.sohu.com/a/272722003_332741" %}

{% embed url="https://www.bilibili.com/video/BV1Tt4y1H7kQ/?spm_id_from=333.999.0.0" %}

{% embed url="https://www.bilibili.com/video/BV1wv4y1G7P8/?spm_id_from=333.999.0.0" %}

{% embed url="https://zhuanlan.zhihu.com/p/157101737" %}

{% embed url="https://zhuanlan.zhihu.com/p/157417868" %}

{% embed url="https://www.bilibili.com/video/BV1CN411X7Ak?p=1&vd_source=f6f10dd471e4def1b221dadd178c9730" %}

{% embed url="https://zhuanlan.zhihu.com/p/665746587" %}

{% embed url="https://www.cnblogs.com/timlly/p/14817455.html" %}
