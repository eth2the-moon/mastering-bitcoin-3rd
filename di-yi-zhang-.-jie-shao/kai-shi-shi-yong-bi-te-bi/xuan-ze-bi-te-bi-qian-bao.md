# 选择比特币钱包

比特币钱包是比特币生态系统中最活跃的应用之一。竞争非常激烈，虽然新的钱包可能正在开发中，但去年的几个钱包已经不再积极维护。许多钱包专注于特定平台或特定用途，有些适合初学者，而有些则充满了面向高级用户的功能。选择钱包是非常主观的，取决于使用情况和用户的专业知识。因此，推荐特定品牌或钱包是毫无意义的。然而，我们可以根据其平台和功能对比特币钱包进行分类，并提供有关所有不同类型的钱包的一些澄清。值得尝试几种不同的钱包，直到找到适合自己需求的一个。

## 比特币钱包的类型

根据平台，比特币钱包可以分为以下几类：

桌面钱包

桌面钱包是最早创建的一种比特币钱包类型，作为参考实现。许多用户使用桌面钱包是因为它们提供的功能、自治权和控制权。但是，作为运行在通用操作系统（如Windows和macOS）上的桌面钱包也存在一定的安全缺陷，因为这些平台通常不安全且配置不良。

移动钱包

移动钱包是最常见的比特币钱包类型。运行在智能手机操作系统（如Apple iOS和Android）上，这些钱包通常是新用户的不错选择。许多钱包设计简单易用，但也有针对高级用户的功能齐全的移动钱包。为了避免下载和存储大量数据，大多数移动钱包从远程服务器检索信息，通过向第三方披露有关您的比特币地址和余额的信息，降低了您的隐私。

Web钱包

Web钱包通过Web浏览器访问，并将用户的钱包存储在第三方拥有的服务器上。这类似于Web邮件，完全依赖于第三方服务器。其中一些服务使用运行在用户浏览器中的客户端代码，这样可以保持比特币密钥控制在用户手中，尽管用户仍然依赖服务器，但这种方式会损害用户的隐私。但大多数服务为了方便起见，从用户那里获取比特币密钥控制权。不建议在第三方系统上存储大量比特币。

硬件签名设备

硬件签名设备是可以使用专用硬件和固件存储密钥并签署交易的设备。它们通常通过USB电缆、近场通信（NFC）或具有QR码的摄像头连接到桌面、移动或Web钱包。通过在专用硬件上处理所有与比特币相关的操作，这些钱包对许多类型的攻击更不易受到影响。有时将硬件签名设备称为“硬件钱包”，但它们需要与功能齐全的钱包配对，以发送和接收交易，并且由配对钱包提供的安全性和隐私性在使用硬件签名设备时起着关键作用。



## 全节点vs轻节点



另一种分类比特币钱包的方法是根据其自治程度以及与比特币网络的交互方式：

全节点

全节点是一种验证比特币所有历史交易（每个用户的每笔交易）的程序。全节点还可以选择存储先前验证的交易并向其他比特币程序提供数据，无论是在同一台计算机上还是通过互联网。全节点使用大量的计算资源——大约相当于每天观看一小时的流媒体视频——但全节点为其用户提供了完全自治。

轻量级客户端

轻量级客户端，也称为简化支付验证（SPV）客户端，连接到全节点或其他远程服务器以接收和发送比特币交易信息，但将用户钱包存储在本地，部分验证接收到的交易，并独立创建输出交易。

第三方API客户端

第三方API客户端是通过与比特币网络直接连接而不是通过连接到比特币网络来与比特币进行交互的第三方API系统进行交互的客户端。钱包可以由用户或第三方服务器存储，但客户端信任远程服务器向其提供准确的信息并保护其隐私。

比特币是一个点对点（P2P）网络。全节点是对等节点：每个节点都可以验证每个确认的交易，并能够向其用户提供具有完全权限的数据。轻量级钱包和其他软件是客户端：每个客户端依赖于一个或多个对等节点提供有效的数据。比特币客户端可以对接收到的部分数据进行辅助验证，并建立与多个对等节点的连接，以减少对单个对等节点完整性的依赖，但是客户端的安全性最终取决于其对等节点的完整性。&#x20;

## 谁控制密钥&#x20;

一个非常重要的额外考虑因素是谁控制密钥。正如我们将在后续章节中看到的那样，对比特币的访问受到“私钥”的控制，这些私钥类似于非常长的PIN码。如果只有您控制这些私钥，那么您就控制着您的比特币。相反，如果您没有控制权，则您的比特币由第三方管理，最终由第三方代表您控制您的资金和账户。根据控制权，密钥管理软件分为两个重要的类别：钱包，您控制密钥；以及具有托管人的资金和账户，某些第三方控制密钥。为了强调这一点，我（安德烈亚斯）创造了这句话：“你的密钥，你的硬币。不是你的密钥，不是你的硬币。”

结合这些分类，许多比特币钱包分为几个组，其中最常见的三个是桌面全节点（您控制密钥）、移动轻量级钱包（您控制密钥）和与第三方的基于Web的账户（您不控制密钥）。不同类别之间的界限有时会模糊，因为软件在多个平台上运行，并且可以以不同的方式与网络进行交互。\
\