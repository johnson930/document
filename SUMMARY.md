# Table of contents

* [首页](README.md)

## 🐤 了解基本概念 <a href="#overview" id="overview"></a>

* [BKCI 是什么？](overview/what-is-bkci.md)
* [BKCI 组件](overview/components.md)
* [5分钟读懂 BKCI 流水线](overview/learn-pipeline-in-5-min.md)
* [术语解释](overview/terminology/README.md)
  * [Pipelines](overview/terminology/pipelines.md)
  * [Stage](overview/terminology/stage.md)
  * [Job](overview/terminology/job.md)
  * [Task](overview/terminology/task.md)
  * [Trigger](overview/terminology/trigger/README.md)
    * [github事件触发](overview/terminology/trigger/github.md)
  * [Variables](overview/terminology/variables.md)

## 👉 使用 BKCI <a href="#tutorials" id="tutorials"></a>

* [创建你的第一条流水线](tutorials/create-first-pipeline.md)
* [关联你的第一个代码库](tutorials/link-first-repo.md)
* [为你的Git工程开启CI](tutorials/enable-git-ci.md)
* [示例](tutorials/examples/README.md)
  * [代码拉取+制品上传+制品下载](tutorials/examples/pull-upload-download.md)
  * [流水线触发方式使用](tutorials/examples/different-triggers.md)
  * [流水线变量使用](tutorials/examples/vars-usage.md)
  * [使用模板创建流水线](tutorials/examples/create-pipeline-by-template.md)
  * [流水线条件判断](tutorials/examples/condition-stage.md)
  * [子流水线](tutorials/examples/children-pipeline.md)
  * [Java Maven Demo](tutorials/examples/java-maven-demo.md)
  * [Node Demo](tutorials/examples/node-demo.md)
* [场景实践](tutorials/scene/README.md)
  * [美术人员自助更新游戏资源](tutorials/scene/Arts-upload-resources.md)
  * [运营人员发布游戏内运营活动](tutorials/scene/operators-upload-resources.md)
  * [客户端多版本构建保持一致](tutorials/scene/client-multi-Consistent.md)
  * [c/c++后台代码的编译加速](tutorials/scene/code-compilation-acceleration.md)
  * [客户端自动化性能测试](tutorials/scene/Client-performance-testing.md)
  * [Pipeline失败的问题定位](tutorials/scene/pipeline-failure-location.md)
  * [移动端内测版本发布管理](tutorials/scene/version-release-management.md)
  * [在转测/发布时使用质量红线](tutorials/scene/release-quality-redline.md)
  * [MergeRequest时使用质量红线](tutorials/scene/mr-quality-redline.md)
  * [企业微信机器人执行流水线](tutorials/scene/wechat-robot-exe.md)
  * [流水线的模版和复制](tutorials/scene/Template-copy-pipeline.md)
  * [管理大量流水线](tutorials/scene/Manage-large-pipelines.md)
  * [UE引擎编译加速](tutorials/scene/UE4-compilation-acceleration.md)
  * [实现发布与回滚](tutorials/scene/Implement-publishing-rollback.md)
  * [集成P4代码库](tutorials/scene/p4-code-base.md)
  * [云环境异常定位](tutorials/scene/Cloud-anomaly-location.md)
  * [流水线互斥及排队](tutorials/scene/Pipeline-exclusion-queue.md)
  * [组建私有构建集群](tutorials/scene/Build-private-clusters.md)
  * [不同流水线间调用](tutorials/scene/call-pipeline-diff.md)
  * [通知发送到钉钉](tutorials/scene/notification-sent-nail.md)

* [客户案例](tutorials/case-study/README.md)
  * [呦尔哈--通过蓝盾提升CI/CD效率](tutorials/case-study/yorha.md)

## 🚀 部署 BKCI <a href="#setup" id="setup"></a>

* [BKCI 系统要求](setup/system-requirements/README.md)
  * [BKCI 硬件规格指南](setup/system-requirements/hardware-specifications.md)
* [使用 One-Docker 运行 BKCI 的学习环境](setup/run-bkci-in-one-docker.md)
* [在生产环境中运行 BKCI](setup/run-bkci-in-prod/README.md)
  * [将 BKCI 一键部署至腾讯云](setup/run-bkci-in-prod/on-tencentcloud.md)
  * [在蓝鲸社区版中部署 BKCI](setup/run-bkci-in-prod/on-bkce.md)

## 📔 产品功能 <a href="#services" id="services"></a>

* [控制台](services/console.md)
* [流水线](services/pipelines/README.md)
  * [流水线触发方式](services/pipelines/pipeline-triggers/README.md)
    * [手动触发](services/pipelines/pipeline-triggers/pipeline-trigger-manual.md)
    * [远程触发](services/pipelines/pipeline-triggers/pipeline-trigger-remote.md)
    * [定时器触发](services/pipelines/pipeline-triggers/pipeline-trigger-timer.md)
    * [gitlab触发](services/pipelines/pipeline-triggers/pipeline-trigger-gitlab.md)
  * [流水线列表页](services/pipelines/pipeline-list.md)
  * [流水线执行历史](services/pipelines/pipeline-build-history.md)
  * [创建/编辑流水线](services/pipelines/pipeline-edit/README.md)
    * [流水线图形化编排](services/pipelines/pipeline-edit/gui.md)
    * [为流水线开启自定义构建号](services/pipelines/pipeline-edit/alias-buildno.md)
    * [锁定流水线](services/pipelines/pipeline-edit/disable-pipeline.md)
  * [流水线任务详情页](services/pipelines/pipeline-build-detail/README.md)
    * [流水线状态信息汇总](services/pipelines/pipeline-build-detail/status.md)
  * [流水线变量](services/pipelines/pipeline-variables/README.md)
    * [变量的基本使用](services/pipelines/pipeline-variables/pipeline-variables-shell-batch.md)
    * [使用变量控制流水线流程](services/pipelines/pipeline-variables/pipeline-variables-flow-control.md)
    * [使用备注变量](services/pipelines/pipeline-variables/pipeline-variables-remark.md)
    * [凭证变量](services/pipelines/pipeline-variables/pipeline-variables-ticket.md)
* [构建资源](services/pools/README.md)
  * [将你的构建机托管至 BKCI](services/pools/self-hosted-agents/README.md)
    * [第三方构建机环境准备](services/pools/self-hosted-agents/prepara-agent.md)
    * [导入Windows构建机](services/pools/self-hosted-agents/windows/README.md)
      * [windows agent启动界面程序的解决办法](services/pools/self-hosted-agents/windows/run-ui.md)
  * [构建机详情页](services/pools/agent-detail.md)
* [凭证管理](services/ticket.md)
* [代码库](services/repo.md)
* [编译加速](services/turbo/README.md)
  * [Linux C/C++ 编译加速](services/turbo/linux\_c\_c++/README.md)
    * [定制Linux C/C++加速方案](services/turbo/linux\_c\_c++/new\_plan.md)
    * [在流水线中进行编译加速](services/turbo/linux\_c\_c++/use\_in\_pipeline.md)
    * [在私有构建机上使用加速](services/turbo/linux\_c\_c++/use\_in\_local.md)
* [制品库](services/bkrepo/README.md)
  * [元数据规范](services/bkrepo/meta.md)
* [代码检查](services/codecc/README.md)
  * [代码检查使用](services/codecc/codecc-usage.md)
  * [代码检查配置](services/codecc/codecc-config.md)
  * [代码检查结果](services/codecc/codecc-result.md)
  * [代码检查规则](services/codecc/codecc-ruleset.md)
  * [代码检查部署所需资源](services/codecc/codecc-cost.md)
* [移动端版本体验](services/client-experience/README.md)
  * [部署移动端版本体验需要的硬件资源](services/client-experience/client-experience-cost.md)
  * [移动端版本体验使用指南](services/client-experience/client-experience-usage.md)

## 🏪 研发商店 <a href="#store" id="store"></a>

* [浏览研发商店](store/store-home.md)
* [流水线模板](store/pipeline-templates.md)
* [CI镜像](store/ci-images/README.md)
  * [构建并托管一个CI镜像](store/ci-images/image-build.md)
  * [发布一个CI镜像](store/ci-images/image-release.md)
* [流水线插件](store/plugins/README.md)
  * [开发一个流水线插件](store/plugins/create-plugin/README.md)
    * [插件开发指引](store/plugins/create-plugin/plugin-dev-guide/README.md)
      * [Java 插件开发指引](store/plugins/create-plugin/plugin-dev-guide/java.md)
      * [Python 插件开发指引](store/plugins/create-plugin/plugin-dev-guide/python.md)
      * [Golang 插件开发指引](store/plugins/create-plugin/plugin-dev-guide/golang.md)
      * [NodeJS 插件开发指引](store/plugins/create-plugin/plugin-dev-guide/nodejs.md)
    * [插件开发规范](store/plugins/create-plugin/plugin-specification.md)
    * [插件配置规范](store/plugins/create-plugin/plugin-config.md)
    * [插件输出规范](store/plugins/create-plugin/plugin-output.md)
    * [插件错误码规范](store/plugins/create-plugin/plugin-error-code.md)
    * [插件发布规范](store/plugins/create-plugin/release.md)
    * [插件自定义UI](store/plugins/create-plugin/plugin-custom-ui.md)
  * [常用插件安装](store/plugins/plugin\_install\_demo.md)
  * [在 BKCI 里使用商店插件](store/plugins/upload-plugin.md)

## 🤝 一起共建 BKCI <a href="#contribute" id="contribute"></a>

* [BKCI 架构](contribute/architecture.md)
* [BKCI 代码结构](contribute/code-framework.md)
* [设计理念](contribute/design.md)
* [文档共建](contribute/document.md)

## ℹ️ 参考信息 <a href="#reference" id="reference"></a>

* [REST API](reference/rest-api/README.md)
  * [使用前必读](reference/rest-api/read-before-use.md)
  * [OPENAPI-项目模板资源](reference/rest-api/project-template-resources/README.md)
    * [批量更新流水线模板实例](reference/rest-api/project-template-resources/batch-update-pipeline-template-example.md)
    * [更新流水线模板](reference/rest-api/project-template-resources/update-the-pipeline-template.md)
    * [批量实例化流水线模板](reference/rest-api/project-template-resources/batch-instantiation-pipeline-template.md)
    * [创建流水线模板](reference/rest-api/project-template-resources/create-a-pipeline-template.md)
    * [获取所有种类流水线模板列表](reference/rest-api/project-template-resources/get-a-list-of-all-kinds-of-pipeline-templates.md)
    * [获取流水线模板的实例列表](reference/rest-api/project-template-resources/get-the-list-of-instances-of-the-pipeline-template.md)
    * [获取流水线模板详情](reference/rest-api/project-template-resources/get-the-details-of-the-pipeline-template.md)
    * [模版管理-获取模版列表](reference/rest-api/project-template-resources/get-a-list-of-templates.md)
    * [删除流水线模板的版本](reference/rest-api/project-template-resources/delete-the-version-of-the-pipeline-template.md)
    * [删除流水线模板](reference/rest-api/project-template-resources/delete-the-pipeline-template.md)
  * [OPENAPI-构建资源](reference/rest-api/build-resources/README.md)
    * [获取签名接口token](reference/rest-api/build-resources/get-the-signature-interface-token.md)
    * [查看签名任务状态信息](reference/rest-api/build-resources/view-signature-task-status-information.md)
    * [获取签后IPA文件下载路径](reference/rest-api/build-resources/get-the-download-path-of-the-signed-ipa-file.md)
    * [签名任务详情](reference/rest-api/build-resources/signature-task-details.md)
  * [OPENAPI-代码提交资源](reference/rest-api/code-submission-resources/README.md)
    * [获取代码提交记录](reference/rest-api/code-submission-resources/get-the-code-submission-record.md)
  * [OPENAPI-代码仓库资源](reference/rest-api/code-warehouse-resources/README.md)
    * [编辑关联代码库](reference/rest-api/code-warehouse-resources/edit-the-associated-code-base.md)
    * [关联代码库](reference/rest-api/code-warehouse-resources/associated-code-base.md)
    * [代码库列表](reference/rest-api/code-warehouse-resources/code-library-list.md)
    * [删除代码库](reference/rest-api/code-warehouse-resources/delete-code-base.md)
  * [OPENAPI-项目资源](reference/rest-api/project-resources/README.md)
    * [修改项目](reference/rest-api/project-resources/modify-the-project.md)
    * [添加指定用户到指定项目用户组](reference/rest-api/project-resources/add-the-specified-user-to-the-specified-project-user-group.md)
    * [创建项目](reference/rest-api/project-resources/create-project.md)
    * [校验项目名称和项目英文名](reference/rest-api/project-resources/verify-the-project-name-and-the-english-name-of-the-project.md)
    * [获取项目信息](reference/rest-api/project-resources/get-project-information.md)
    * [查询所有项目](reference/rest-api/project-resources/query-all-items.md)
  * [OPENAPI-流水线资源](reference/rest-api/pipeline-resources/README.md)
    * [更新流水线设置](reference/rest-api/pipeline-resources/update-pipeline-settings.md)
    * [还原流水线编排](reference/rest-api/pipeline-resources/reduction-pipeline-orchestration.md)
    * [更新流水线编排和设置](reference/rest-api/pipeline-resources/update-pipeline-layout-and-settings.md)
    * [编辑流水线编排](reference/rest-api/pipeline-resources/edit-pipeline-layout.md)
    * [导入新流水线, 包含流水线编排和设置](reference/rest-api/pipeline-resources/import-new-pipeline.md)
    * [批量获取流水线编排与配置](reference/rest-api/pipeline-resources/batch-get-pipeline-layout-and-configuration.md)
    * [流水线重命名](reference/rest-api/pipeline-resources/pipeline-renaming.md)
    * [复制流水线编排](reference/rest-api/pipeline-resources/copy-pipeline-orchestration.md)
    * [新建流水线编排](reference/rest-api/pipeline-resources/new-pipeline-orchestration.md)
    * [获取流水线状态](reference/rest-api/pipeline-resources/get-the-status-of-the-pipeline.md)
    * [获取流水线编排](reference/rest-api/pipeline-resources/get-the-pipeline-orchestration.md)
    * [获取项目的流水线列表](reference/rest-api/pipeline-resources/get-the-pipeline-list-of-the-project.md)
    * [删除流水线编排](reference/rest-api/pipeline-resources/delete-the-pipeline-orchestration.md)
  * [OPENAPI-流水线分组](reference/rest-api/pipeline-grouping/README.md)
    * [更改标签](reference/rest-api/pipeline-grouping/change-label.md)
    * [更改分组](reference/rest-api/pipeline-grouping/change-group.md)
    * [添加标签](reference/rest-api/pipeline-grouping/add-tag.md)
    * [添加分组](reference/rest-api/pipeline-grouping/add-group.md)
    * [获取所有分组信息](reference/rest-api/pipeline-grouping/get-all-group-information.md)
    * [删除标签](reference/rest-api/pipeline-grouping/remove-label.md)
    * [删除分组](reference/rest-api/pipeline-grouping/delete-group.md)
  * [OPENAPI-迁移](reference/rest-api/migrate/README.md)
    * [关联iam项目](reference/rest-api/migrate/associated-iam-project.md)
    * [获取项目下pipelineId+自增id](reference/rest-api/migrate/get-the-pipelineid-and-auto-increment-id-under-the-project.md)
  * [OPENAPI-研发市场资源](reference/rest-api/r-and-d-market-resources/README.md)
    * [安装研发商店模板到项目](reference/rest-api/r-and-d-market-resources/install-the-r-and-d-store-template-into-the-project.md)
  * [OPENAPI-构建日志资源](reference/rest-api/build-log-resources/README.md)
    * [获取更多日志](reference/rest-api/build-log-resources/get-more-logs.md)
    * [根据构建ID获取初始化所有日志](reference/rest-api/build-log-resources/obtain-and-initialize-all-logs-according-to-the-build-id.md)
    * [下载日志接口](reference/rest-api/build-log-resources/download-log-interface.md)
    * [获取某行后的日志](reference/rest-api/build-log-resources/get-the-log-after-a-certain-line.md)
  * [OPENAPI-证书资源](reference/rest-api/certificate-resources/README.md)
    * [编辑凭据](reference/rest-api/certificate-resources/edit-credentials.md)
    * [新增凭据](reference/rest-api/certificate-resources/add-credentials.md)
    * [获取凭据](reference/rest-api/certificate-resources/get-credentials.md)
    * [获取用户拥有对应权限凭据列表](reference/rest-api/certificate-resources/obtain-the-list-of-credentials-that-the-user-has-corresponding-permissions.md)
    * [删除凭据](reference/rest-api/certificate-resources/delete-credentials.md)
  * [OPENAPI-callback资源](reference/rest-api/callback-resource/README.md)
    * [callback回调重试](reference/rest-api/callback-resource/callback-callback-to-retry.md)
    * [批量创建callback回调](reference/rest-api/callback-resource/create-callbacks-in-batches.md)
    * [创建callback回调](reference/rest-api/callback-resource/create-callback-callback.md)
    * [callback回调执行历史记录](reference/rest-api/callback-resource/callback-execution-history.md)
    * [callback回调列表](reference/rest-api/callback-resource/callback-list.md)
    * [callback回调移除](reference/rest-api/callback-resource/callback-callback-removed.md)
  * [OPENAPI-构建资源](reference/rest-api/build-resources-1/README.md)
    * [启动构建](reference/rest-api/build-resources-1/start-the-build.md)
    * [获取构建中的变量值](reference/rest-api/build-resources-1/get-the-value-of-the-variable-in-the-build.md)
    * [停止构建](reference/rest-api/build-resources-1/stop-building.md)
    * [手动审核启动阶段](reference/rest-api/build-resources-1/manual-review-of-the-start-up-phase.md)
    * [重试构建-重试或者跳过失败插件](reference/rest-api/build-resources-1/retry-the-build.md)
    * [操作暂停插件](reference/rest-api/build-resources-1/operation-pause-plugin.md)
    * [获取流水线手动启动参数](reference/rest-api/build-resources-1/obtain-the-manual-start-parameters-of-the-pipeline.md)
    * [获取流水线构建历史](reference/rest-api/build-resources-1/get-pipeline-construction-history.md)
    * [查看构建状态信息](reference/rest-api/build-resources-1/view-build-status-information.md)
    * [构建详情](reference/rest-api/build-resources-1/build-details.md)
  * [OPENAPI-插件资源](reference/rest-api/plugin-resources/README.md)
    * [安装插件到项目](reference/rest-api/plugin-resources/install-the-plugin-to-the-project.md)
    * [根据插件代码获取插件统计信息](reference/rest-api/plugin-resources/get-plug-in-statistics-according-to-the-plug-in-code.md)
    * [根据插件代码获取使用的流水线详情](reference/rest-api/plugin-resources/get-the-details-of-the-pipeline-used-according-to-the-plug-in-code.md)
    * [根据插件代码获取插件详细信息](reference/rest-api/plugin-resources/get-plug-in-details-according-to-the-plug-in-code.md)
  * [OPENAPI-构建产物资源](reference/rest-api/build-product-resources/README.md)
    * [获取用户下载链接](reference/rest-api/build-product-resources/get-user-download-link.md)
    * [根据元数据获取文件](reference/rest-api/build-product-resources/get-files-based-on-metadata.md)
  * [OPENAPI-构建产物托管任务资源](reference/rest-api/build-product-hosting-task-resources/README.md)
    * [清理文件托管任务](reference/rest-api/build-product-hosting-task-resources/clean-up-file-hosting-tasks.md)
    * [创建文件托管任务](reference/rest-api/build-product-hosting-task-resources/create-file-hosting-task.md)
    * [查询文件托管任务状态](reference/rest-api/build-product-hosting-task-resources/query-file-hosting-task-status.md)
  * [OPENAPI-环境管理-构建机管理](reference/rest-api/build-machine-management/README.md)
    * [根据hashId获取项目节点列表(不校验权限)](reference/rest-api/build-machine-management/get-the-list-of-project-nodes-according-to-hashid.md)
    * [根据环境的hashId获取指定项目指定环境下节点列表(不校验权限)](reference/rest-api/build-machine-management/get-the-list-of-nodes-in-the-specified-environment-of-the-specified-project-according-to-the-hashid.md)
    * [根据环境名称获取环境信息(不校验权限)](reference/rest-api/build-machine-management/obtain-environmental-information-based-on-the-environmental-name.md)
    * [根据hashId(多个)获取环境信息(不校验权限)](reference/rest-api/build-machine-management/obtain-environmental-information-based-on-hashid-multiple.md)
    * [获取指定构建机状态](reference/rest-api/build-machine-management/get-the-status-of-the-specified-build-machine.md)
    * [获取项目下第三方构建机列表](reference/rest-api/build-machine-management/get-the-list-of-third-party-build-machines-under-the-project.md)
    * [获取用户有权限使用的服务器列表](reference/rest-api/build-machine-management/get-the-list-of-servers-that-the-user-has-permission-to-use.md)
    * [获取构建节点信息（扩展接口）](reference/rest-api/build-machine-management/get-build-node-information.md)
    * [获取构建节点信息（扩展接口）](reference/rest-api/build-machine-management/get-build-node-information-extension-ports.md)
    * [获取用户有权限使用的环境列表](reference/rest-api/build-machine-management/get-the-list-of-environments-that-the-user-has-permission-to-use.md)
  * [QUALITY-质量红线相关](reference/rest-api/quality-red-line-related/README.md)
    * [更新拦截规则列表](reference/rest-api/quality-red-line-related/update-the-list-of-blocking-rules.md)
    * [创建拦截规则](reference/rest-api/quality-red-line-related/create-blocking-rules.md)
    * [获取拦截规则列表](reference/rest-api/quality-red-line-related/get-the-list-of-blocking-rules.md)
    * [获取拦截记录](reference/rest-api/quality-red-line-related/obtain-interception-records.md)
    * [删除拦截规则列表](reference/rest-api/quality-red-line-related/delete-the-list-of-blocking-rules.md)
  * [WEBHOOK-代码事件触发](reference/rest-api/code-event-trigger/README.md)
    * [获取流水线的webhook构建日志列表](reference/rest-api/code-event-trigger/get-the-pipelines-webhook-build-log-list.md)
    * [获取流水线的webhook列表](reference/rest-api/code-event-trigger/get-the-webhook-list-of-the-pipeline.md)
* [数据库设计文档](reference/DB-doc/README.md)
  * [devops\_ci\_auth](reference/DB-doc/devops\_ci\_auth.md)
  * [devops\_ci\_sign](reference/DB-doc/devops\_ci\_sign.md)
  * [devops\_ci\_artifactory](reference/DB-doc/devops\_ci\_artifactory.md)
  * [devops\_ci\_repository](reference/DB-doc/devops\_ci\_repository.md)
  * [devops\_ci\_plugin](reference/DB-doc/devops\_ci\_plugin.md)
  * [devops\_ci\_project](reference/DB-doc/devops\_ci\_project.md)
  * [devops\_ci\_quality](reference/DB-doc/devops\_ci\_quality.md)
  * [devops\_ci\_store](reference/DB-doc/devops\_ci\_store.md)
  * [devops\_ci\_log](reference/DB-doc/devops\_ci\_log.md)
  * [devops\_ci\_dispatch](reference/DB-doc/devops\_ci\_dispatch.md)
  * [devops\_ci\_image](reference/DB-doc/devops\_ci\_image.md)
  * [devops\_ci\_environment](reference/DB-doc/devops\_ci\_environment.md)
  * [devops\_ci\_op](reference/DB-doc/devops\_ci\_op.md)
  * [devops\_ci\_notify](reference/DB-doc/devops\_ci\_notify.md)
  * [devops\_ci\_openapi](reference/DB-doc/devops\_ci\_openapi.md)
  * [devops\_ci\_ticket](reference/DB-doc/devops\_ci\_ticket.md)
  * [devops\_ci\_process](reference/DB-doc/devops\_ci\_process.md)
  * [devops\_ci\_measure](reference/DB-doc/devops\_ci\_measure.md)
* [预定义变量列表](reference/pre-define-var/README.md)
  * [gitlab事件触发](reference/pre-define-var/gitlab.md)
* [FAQS](reference/faqs/README.md)
  * [流水线FAQ](reference/faqs/pipeline-faqs.md)
  * [代码检查FAQ](reference/faqs/codecc-faqs.md)
  * [编译加速FAQ](reference/faqs/turbo-faqs.md)
  * [已知问题](reference/faqs/known-issues.md)
* [系统限制](reference/limit/README.md)
  * [流水线复杂度限制](reference/limit/pipeline-limit.md)
* [蓝鲸使用学习材料](reference/bk-tutorial/README.md)

***

* [返回 BKCI 官网](https://bkci.net)
