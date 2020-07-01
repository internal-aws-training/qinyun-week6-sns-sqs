# qinyun-week6-sns-sqs

## SNS 是什么服务？解决什么问题？

Amazon Simple Notification Service (SNS) 是一种高度可用、持久、安全、完全托管的发布/订阅消息收发服务，可以轻松分离微服务、分布式系统和无服务器应用程序。Amazon SNS 提供了面向高吞吐量、多对多推送式消息收发的主题。借助 Amazon SNS 主题，发布系统可以向大量订阅终端节点（包括 Amazon SQS 队列、AWS Lambda 函数和 HTTP/S Webhook 等）扇出消息，从而实现并行处理。此外，SNS 可用于使用移动推送、短信和电子邮件向最终用户扇出通知。

## SQS 是什么服务？解决什么问题？

<div class="text-purple">
Amazon Simple Queue Service (SQS) 是一种完全托管的消息队列服务，可让您分离和扩展微服务、分布式系统和无服务器应用程序。SQS 消除了与管理和运营消息型中间件相关的复杂性和开销，并使开发人员能够专注于重要工作。借助 SQS，您可以在软件组件之间发送、存储和接收任何规模的消息，而不会丢失消息，并且无需其他服务即可保持可用。使用 AWS 控制台、命令行界面或您选择的 SDK 和三个简单的命令，在几分钟内即可开始使用 SQS。
</div>