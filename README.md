# 模型上下文协议服务器

此存储库是[模型上下文协议](https://modelcontextprotocol.io/)（MCP）的*参考实现*集合，同时也包含社区构建的服务器和附加资源的引用。

此存储库中的服务器展示了MCP的多样性和扩展性，演示了如何使用它为大型语言模型（LLM）提供对工具和数据源的安全、可控访问。每个MCP服务器均使用[Typescript MCP SDK](https://github.com/modelcontextprotocol/typescript-sdk)或[Python MCP SDK](https://github.com/modelcontextprotocol/python-sdk)实现。

> 注意：本README中的列表按字母顺序维护，以减少添加新项时的合并冲突。

## 🌟 参考服务器

这些服务器旨在展示MCP功能以及TypeScript和Python SDK。

- **[AWS KB Retrieval](src/aws-kb-retrieval-server)** - 使用Bedrock Agent Runtime从AWS知识库检索
- **[Brave Search](src/brave-search)** - 使用Brave的搜索API进行网络和本地搜索
- **[EverArt](src/everart)** - 使用各种模型进行AI图像生成
- **[Everything](src/everything)** - 包含提示、资源和工具的参考/测试服务器
- **[Fetch](src/fetch)** - 网页内容获取和转换，以优化LLM使用
- **[Filesystem](src/filesystem)** - 具有可配置访问控制的安全文件操作
- **[Git](src/git)** - 读取、搜索和操作Git存储库的工具
- **[GitHub](src/github)** - 存储库管理、文件操作和GitHub API集成
- **[GitLab](src/gitlab)** - GitLab API，支持项目管理
- **[Google Drive](src/gdrive)** - Google Drive的文件访问和搜索功能
- **[Google Maps](src/google-maps)** - 位置服务、导航和地点详情
- **[Memory](src/memory)** - 基于知识图谱的持久内存系统
- **[PostgreSQL](src/postgres)** - 只读数据库访问，支持架构检查
- **[Puppeteer](src/puppeteer)** - 浏览器自动化和网页抓取
- **[Redis](src/redis)** - 与Redis键值存储交互
- **[Sentry](src/sentry)** - 从Sentry.io检索和分析问题
- **[Sequential Thinking](src/sequentialthinking)** - 通过思维序列进行动态和反思性问题解决
- **[Slack](src/slack)** - 频道管理和消息传递功能
- **[Sqlite](src/sqlite)** - 数据库交互和商业智能功能
- **[Time](src/time)** - 时间和时区转换功能

## 🤝 第三方服务器

### 🎖️ 官方集成

官方集成由构建生产就绪MCP服务器的公司维护，用于其平台。

- <img height="12" width="12" src="https://www.21st.dev/favicon.ico" alt="21st.dev Logo" /> **[21st.dev Magic](https://github.com/21st-dev/magic-mcp)** - 创建受21st.dev最佳设计工程师启发的精美UI组件。
- <img height="12" width="12" src="https://invoxx-public-bucket.s3.eu-central-1.amazonaws.com/frontend-resources/adfin-logo-small.svg" alt="Adfin Logo" /> **[Adfin](https://github.com/Adfin-Engineering/mcp-server-adfin)** - 您获取报酬所需的唯一平台 - 所有支付集中在一处，支持发票和会计对账，使用[Adfin](https://www.adfin.com/)。
- <img height="12" width="12" src="https://www.agentql.com/favicon/favicon.png" alt="AgentQL Logo" /> **[AgentQL](https://github.com/tinyfish-io/agentql-mcp)** - 使AI代理能够从非结构化网络中获取结构化数据，使用[AgentQL](https://www.agentql.com/)。
- <img height="12" width="12" src="https://agentrpc.com/favicon.ico" alt="AgentRPC Logo" /> **[AgentRPC](https://github.com/agentrpc/agentrpc)** - 使用[AgentRPC](https://www.agentrpc.com/)跨网络边界连接到任何函数、任何语言。
- <img height="12" width="12" src="https://aiven.io/favicon.ico" alt="Aiven Logo" /> **[Aiven](https://github.com/Aiven-Open/mcp-aiven)** - 浏览您的[Aiven项目](https://go.aiven.io/mcp-server)并与PostgreSQL®、Apache Kafka®、ClickHouse®和OpenSearch®服务交互
- <img height="12" width="12" src="https://apify.com/favicon.ico" alt="Apify Logo" /> **[Apify](https://github.com/apify/actors-mcp-server)** - [Actors MCP Server](https://apify.com/apify/actors-mcp-server)：使用3000多个预构建的云工具从网站、电子商务、社交媒体、搜索引擎、地图等提取数据
- <img height="12" width="12" src="https://2052727.fs1.hubspotusercontent-na1.net/hubfs/2052727/cropped-cropped-apimaticio-favicon-1-32x32.png" alt="APIMatic Logo" /> **[APIMatic MCP](https://github.com/apimatic/apimatic-validator-mcp)** - APIMatic MCP服务器用于验证OpenAPI规范，使用[APIMatic](https://www.apimatic.io/)。该服务器处理OpenAPI文件并返回验证摘要，借助APIMatic的API。
- <img height="12" width="12" src="https://resources.audiense.com/hubfs/favicon-1.png" alt="Audiense Logo" /> **[Audiense Insights](https://github.com/AudienseCo/mcp-audiense-insights)** - 从[Audiense](https://www.audiense.com/products/audiense-insights)报告中获取营销洞察和受众分析，涵盖人口统计、文化、影响者和内容参与分析。
- <img height="12" width="12" src="https://axiom.co/favicon.ico" alt="Axiom Logo" /> **[Axiom](https://github.com/axiomhq/mcp-server-axiom)** - 使用自然语言查询和分析您的Axiom日志、跟踪和其他所有事件数据
- <img height="12" width="12" src="https://www.bankless.com/favicon.ico" alt="Bankless Logo" /> **[Bankless Onchain](https://github.com/bankless/onchain-mcp)** - 查询链上数据，如ERC20代币、交易历史、智能合约状态。
- <img height="12" width="12" src="https://bicscan.io/favicon.png" alt="BICScan Logo" /> **[BICScan](https://github.com/ahnlabio/bicscan-mcp)** - EVM区块链地址（EOA、CA、ENS）甚至域名的风险评分/资产持有。
- <img height="12" width="12" src="https://www.box.com/favicon.ico" alt="Box Logo" /> **[Box](https://github.com/box-community/mcp-server-box)** - 通过Box AI与智能内容管理平台交互。
- <img height="12" width="12" src="https://browserbase.com/favicon.ico" alt="Browserbase Logo" /> **[Browserbase](https://github.com/browserbase/mcp-server-browserbase)** - 在云端自动化浏览器交互（例如网页导航、数据提取、表单填写等）
- <img height="12" width="12" src="https://www.chargebee.com/static/resources/brand/favicon.png" /> **[Chargebee](https://github.com/chargebee/agentkit/tree/main/modelcontextprotocol)** - 将AI代理连接到[Chargebee平台](https://www.chargebee.com)的MCP服务器。
- <img height="12" width="12" src="https://trychroma.com/_next/static/media/chroma-logo.ae2d6e4b.svg" /> **[Chroma](https://github.com/chroma-core/chroma-mcp)** - 使用开源AI应用程序数据库进行嵌入、向量搜索、文档存储和全文搜索
- <img height="12" width="12" src="https://www.chronulus.com/favicon/chronulus-logo-blue-on-alpha-square-128x128.ico" alt="Chronulus AI Logo" /> **[Chronulus AI](https://github.com/ChronulusAI/chronulus-mcp)** - 使用Chronulus AI预测和预测代理预测任何事物。
- <img height="12" width="12" src="https://clickhouse.com/favicon.ico" alt="ClickHouse Logo" /> **[ClickHouse](https://github.com/ClickHouse/mcp-clickhouse)** - 查询您的[ClickHouse](https://clickhouse.com/)数据库服务器。
- <img height="12" width="12" src="https://cdn.simpleicons.org/cloudflare" /> **[Cloudflare](https://github.com/cloudflare/mcp-server-cloudflare)** - 在Cloudflare开发者平台上部署、配置和查询您的资源（例如Workers/KV/R2/D1）
- <img height="12" width="12" src="https://www.comet.com/favicon.ico" alt="Comet Logo" /> **[Comet Opik](https://github.com/comet-ml/opik-mcp)** - 使用自然语言查询和分析您的[Opik](https://github.com/comet-ml/opik)日志、跟踪、提示以及所有其他LLM遥测数据。
- <img height="12" width="12" src="https://www.convex.dev/favicon.ico" /> **[Convex](https://stack.convex.dev/convex-mcp-server)** - 检查和查询部署到Convex的应用程序。
- <img height="12" width="12" src="http://app.itsdart.com/static/img/favicon.png" alt="Dart Logo" /> **[Dart](https://github.com/its-dart/dart-mcp-server)** - 与[Dart](https://itsdart.com)中的任务、文档和项目数据交互，这是一个AI原生项目管理工具
- <img height="12" width="12" src="https://www.devhub.com/img/upload/favicon-196x196-dh.png" alt="DevHub Logo" /> **[DevHub](https://github.com/devhub/devhub-cms-mcp)** - 在[DevHub](https://www.devhub.com) CMS平台内管理和利用网站内容
- <img height="12" width="12" src="https://e2b.dev/favicon.ico" alt="E2B Logo" /> **[E2B](https://github.com/e2b-dev/mcp-server)** - 在[E2B](https://e2b.dev)托管的安全沙箱中运行代码
- <img height="12" width="12" src="https://static.edubase.net/media/brand/favicon/favicon-32x32.png" alt="EduBase Logo" /> **[EduBase](https://github.com/EduBase/MCP)** - 与[EduBase](https://www.edubase.net)交互，这是一个具有高级测验、考试管理和内容组织功能的综合电子学习平台
- <img height="12" width="12" src="https://esignatures.com/favicon.ico" alt="eSignatures Logo" /> **[eSignatures](https://github.com/esignaturescom/mcp-server-esignatures)** - 用于起草、审查和发送具有约束力的合同的合同和模板管理。
- <img height="12" width="12" src="https://exa.ai/images/favicon-32x32.png" alt="Exa Logo" /> **[Exa](https://github.com/exa-labs/exa-mcp-server)** - 由[Exa](https://exa.ai)为AI打造的搜索引擎
- <img height="12" width="12" src="https://fewsats.com/favicon.svg" alt="Fewsats Logo" /> **[Fewsats](https://github.com/Fewsats/fewsats-mcp)** - 使用[Fewsats](https://fewsats.com)使AI代理能够以安全的方式购买任何东西
- <img height="12" width="12" src="https://fibery.io/favicon.svg" alt="Fibery Logo" /> **[Fibery](https://github.com/Fibery-inc/fibery-mcp-server)** - 在您的[Fibery](https://fibery.io)工作空间中执行查询和实体操作。
- <img height="12" width="12" src="https://financialdatasets.ai/favicon.ico" alt="Financial Datasets Logo" /> **[Financial Datasets](https://github.com/financial-datasets/mcp-server)** - 为AI代理打造的股票市场API
- <img height="12" width="12" src="https://firecrawl.dev/favicon.ico" alt="Firecrawl Logo" /> **[Firecrawl](https://github.com/mendableai/firecrawl-mcp-server)** - 使用[Firecrawl](https://firecrawl.dev)提取网页数据
- <img height="12" width="12" src="https://fireproof.storage/favicon.ico" alt="Fireproof Logo" /> **[Fireproof](https://github.com/fireproof-storage/mcp-database-server)** - 具有实时同步的不可变账本数据库
- <img height="12" width="12" src="https://gitee.com/favicon.ico" alt="Gitee Logo" /> **[Gitee](https://github.com/oschina/mcp-gitee)** - Gitee API集成，存储库、问题和拉取请求管理等。
- <img height="12" width="12" src="https://cdn.prod.website-files.com/6605a2979ff17b2cd1939cd4/6605a460de47e7596ed84f06_icon256.png" alt="gotoHuman Logo" /> **[gotoHuman](https://github.com/gotohuman/gotohuman-mcp-server)** - 人机交互平台 - 允许AI代理和自动化将请求发送到您的[gotoHuman](https://www.gotohuman.com)收件箱以获得批准。
- <img height="12" width="12" src="https://grafana.com/favicon.ico" alt="Grafana Logo" /> **[Grafana](https://github.com/grafana/mcp-grafana)** - 在您的Grafana实例中搜索仪表板、调查事件和查询数据源
- <img height="12" width="12" src="https://framerusercontent.com/images/KCOWBYLKunDff1Dr452y6EfjiU.png" alt="Graphlit Logo" /> **[Graphlit](https://github.com/graphlit/graphlit-mcp-server)** - 从Slack到Gmail再到播客源，摄取任何内容，并将其加入可搜索的[Graphlit](https://www.graphlit.com)项目中，同时支持网络爬取。
- <img height="12" width="12" src="https://greptime.com/favicon.ico" alt="Greptime Logo" /> **[GreptimeDB](https://github.com/GreptimeTeam/greptimedb-mcp-server)** - 为AI助手提供安全、结构化的方式，以探索和分析[GreptimeDB](https://github.com/GreptimeTeam/greptimedb)中的数据。
- <img height="12" width="12" src="https://img.alicdn.com/imgextra/i3/O1CN01d9qrry1i6lTNa2BRa_!!6000000004364-2-tps-218-200.png" alt="Hologres Logo" /> **[Hologres](https://github.com/aliyun/alibabacloud-hologres-mcp-server)** - 连接到[Hologres](https://www.alibabacloud.com/en/product/hologres)实例，获取表元数据，查询和分析数据。
- <img height="12" width="12" src="https://hyperbrowser-assets-bucket.s3.us-east-1.amazonaws.com/Hyperbrowser-logo.png" alt="Hyperbrowsers23 Logo" /> **[Hyperbrowser](https://github.com/hyperbrowserai/mcp)** - [Hyperbrowser](https://www.hyperbrowser.ai/)是赋予AI代理并实现轻松、可扩展浏览器自动化的下一代平台。
- **[IBM wxflows](https://github.com/IBM/wxflows/tree/main/examples/mcp/javascript)** - IBM提供的工具平台，用于构建、测试和部署任何数据源的工具
- <img height="12" width="12" src="https://forevervm.com/icon.png" alt="ForeverVM Logo" /> **[ForeverVM](https://github.com/jamsocket/forevervm/tree/main/javascript/mcp-server)** - 在代码沙箱中运行Python。
- <img height="12" width="12" src="https://www.getinboxzero.com/icon.png" alt="Inbox Zero Logo" /> **[Inbox Zero](https://github.com/elie222/inbox-zero/tree/main/apps/mcp-server)** - 用于电子邮件的AI个人助理[Inbox Zero](https://www.getinboxzero.com)
- <img height="12" width="12" src="https://inkeep.com/favicon.ico" alt="Inkeep Logo" /> **[Inkeep](https://github.com/inkeep/mcp-server-python)** - 由[Inkeep](https://inkeep.com)提供支持的RAG搜索您的内容
- <img height="12" width="12" src="https://integration.app/favicon.ico" alt="Integration App Icon" /> **[Integration App](https://github.com/integration-app/mcp-server)** - 代表您的客户与任何其他SaaS应用程序交互。
- <img height="12" width="12" src="https://cdn.simpleicons.org/jetbrains" /> **[JetBrains](https://github.com/JetBrains/mcp-jetbrains)** – 使用JetBrains IDE处理您的代码
- <img height="12" width="12" src="https://kagi.com/favicon.ico" alt="Kagi Logo" /> **[Kagi Search](https://github.com/kagisearch/kagimcp)** - 使用Kagi的搜索API搜索网络
- <img height="12" width="12" src="https://connection.keboola.com/favicon.ico" alt="Keboola Logo" /> **[Keboola](https://github.com/keboola/keboola-mcp-server)** - 在一个直观的平台上构建强大的数据工作流、集成和分析。
- <img height="12" width="12" src="https://logfire.pydantic.dev/favicon.ico" alt="Logfire Logo" /> **[Logfire](https://github.com/pydantic/logfire-mcp)** - 通过Logfire提供对OpenTelemetry跟踪和指标的访问。
- <img height="12" width="12" src="https://langfuse.com/favicon.ico" alt="Langfuse Logo" /> **[Langfuse Prompt Management](https://github.com/langfuse/mcp-server-langfuse)** - 用于协作编辑、版本控制、评估和发布提示的开源工具。
- <img height="12" width="12" src="https://lingo.dev/favicon.ico" alt="Lingo.dev Logo" /> **[Lingo.dev](https://github.com/lingodotdev/lingo.dev/blob/main/mcp.md)** - 使用[Lingo.dev](https://lingo.dev)本地化引擎使您的AI代理能够说地球上的每一种语言。
- <img height="12" width="12" src="https://www.mailgun.com/favicon.ico" alt="Mailgun Logo" /> **[Mailgun](https://github.com/mailgun/mailgun-mcp-server)** - 与Mailgun API交互。
- <img height="12" width="12" src="https://www.make.com/favicon.ico" alt="Make Logo" /> **[Make](https://github.com/integromat/make-mcp-server)** - 将您的[Make](https://www.make.com/)场景转化为AI助手的可调用工具。
- <img height="12" width="12" src="https://www.meilisearch.com/favicon.ico" alt="Meilisearch Logo" /> **[Meilisearch](https://github.com/meilisearch/meilisearch-mcp)** - 与Meilisearch交互和查询（全文和语义搜索API）
- <img height="12" width="12" src="https://metoro.io/static/images/logos/Metoro.svg" /> **[Metoro](https://github.com/metoro-io/metoro-mcp-server)** - 查询和交互由Metoro监控的Kubernetes环境
- <img height="12" width="12" src="https://milvus.io/favicon-32x32.png" /> **[Milvus](https://github.com/zilliztech/mcp-server-milvus)** - 在您的Milvus向量数据库中搜索、查询和交互数据。
- <img height="12" width="12" src="https://www.motherduck.com/favicon.ico" alt="MotherDuck Logo" /> **[MotherDuck](https://github.com/motherduckdb/mcp-server-motherduck)** - 使用MotherDuck和本地DuckDB查询和分析数据
- <img height="12" width="12" src="https://needle-ai.com/images/needle-logo-orange-2-rounded.png" alt="Needle AI Logo" /> **[Needle](https://github.com/needle-ai/needle-mcp)** - 开箱即用的生产就绪RAG，用于搜索和检索您自己的文档数据。
- <img height="12" width="12" src="https://neo4j.com/favicon.ico" alt="Neo4j Logo" /> **[Neo4j](https://github.com/neo4j-contrib/mcp-neo4j/)** - Neo4j图形数据库服务器（模式 + 读/写-cypher）和独立的基于图形数据库的内存
- <img height="12" width="12" src="https://avatars.githubusercontent.com/u/183852044?s=48&v=4" alt="Neon Logo" /> **[Neon](https://github.com/neondatabase/mcp-server-neon)** - 与Neon无服务器Postgres平台交互
- <img height="12" width="12" src="https://avatars.githubusercontent.com/u/82347605?s=48&v=4" alt="OceanBase Logo" /> **[OceanBase](https://github.com/oceanbase/mcp-oceanbase)** - OceanBase数据库及其工具的MCP服务器
- <img height="12" width="12" src="https://docs.octagonagents.com/logo.svg" alt="Octagon Logo" /> **[Octagon](https://github.com/OctagonAI/octagon-mcp-server)** - 提供实时投资研究，涵盖广泛的私人和公共市场数据。
- <img height="12" width="12" src="https://oxylabs.io/favicon.ico" alt="Oxylabs Logo" /> **[Oxylabs](https://github.com/oxylabs/oxylabs-mcp)** - 使用Oxylabs Web API抓取网站，支持动态渲染和结构化数据提取的解析。
- <img height="12" width="12" src="https://www.perplexity.ai/favicon.ico" alt="Perplexity Logo" /> **[Perplexity](https://github.com/ppl-ai/modelcontextprotocol)** - 一个连接到Perplexity的Sonar API的MCP服务器，使对话AI能够进行实时网络范围的研究。
- <img height="12" width="12" src="https://qdrant.tech/img/brand-resources-logos/logomark.svg" /> **[Qdrant](https://github.com/qdrant/mcp-server-qdrant/)** - 在Qdrant向量搜索引擎上实现语义内存层
- <img height="12" width="12" src="https://www.ramp.com/favicon.ico" /> **[Ramp](https://github.com/ramp-public/ramp-mcp)** - 与[Ramp](https://ramp.com)的开发者API交互，利用LLM运行您的支出分析并获得洞察
- **[Raygun](https://github.com/MindscapeHQ/mcp-server-raygun)** - 与您的Raygun账户上的崩溃报告和实时用户监控数据交互
- <img height="12" width="12" src="https://www.rember.com/favicon.ico" alt="Rember Logo" /> **[Rember](https://github.com/rember/rember-mcp)** - 在[Rember](https://rember.com)中创建间隔重复记忆卡，以记住您在聊天中学到的任何内容
- <img height="12" width="12" src="https://riza.io/favicon.ico" alt="Riza logo" /> **[Riza](https://github.com/riza-io/riza-mcp)** - 由[Riza](https://riza.io)提供的LLM任意代码执行和工具使用平台
- <img height="12" width="12" src="https://pics.fatwang2.com/56912e614b35093426c515860f9f2234.svg" /> **[Search1API](https://github.com/fatwang2/search1api-mcp)** - 用于搜索、爬取和网站地图的单一API
- <img height="12" width="12" src="https://screenshotone.com/favicon.ico" alt="ScreenshotOne Logo" /> **[ScreenshotOne](https://github.com/screenshotone/mcp/)** - 使用[ScreenshotOne](https://screenshotone.com/)渲染网站截图
- <img height="12" width="12" src="https://semgrep.dev/favicon.ico" alt="Semgrep Logo" /> **[Semgrep](https://github.com/semgrep/mcp)** - 使用[Semgrep](https://semgrep.dev/)使AI代理能够保护代码。
- <img height="12" width="12" src="https://www.singlestore.com/favicon-32x32.png?v=277b9cbbe31e8bc416504cf3b902d430"/> **[SingleStore](https://github.com/singlestore-labs/mcp-server-singlestore)** - 与SingleStore数据库平台交互
- <img height="12" width="12" src="https://www.starrocks.io/favicon.ico" alt="StarRocks Logo" /> **[StarRocks](https://github.com/StarRocks/mcp-server-starrocks)** - 与[StarRocks](https://www.starrocks.io/)交互
- <img height="12" width="12" src="https://stripe.com/favicon.ico" alt="Stripe Logo" /> **[Stripe](https://github.com/stripe/agent-toolkit)** - 与Stripe API交互
- <img height="12" width="12" src="https://tavily.com/favicon.ico" alt="Tavily Logo" /> **[Tavily](https://github.com/tavily-ai/tavily-mcp)** - 为AI代理设计的搜索引擎（搜索+提取），由[Tavily](https://tavily.com/)提供支持
- <img height="12" width="12" src="https://thirdweb.com/favicon.ico" alt="Thirdweb Logo" /> **[Thirdweb](https://github.com/thirdweb-dev/ai/tree/main/python/thirdweb-mcp)** - 读/写超过2000个区块链，支持数据查询、合约分析/部署和交易执行，由[Thirdweb](https://thirdweb.com/)提供支持
- <img height="12" width="12" src="https://www.tinybird.co/favicon.ico" alt="Tinybird Logo" /> **[Tinybird](https://github.com/tinybirdco/mcp-tinybird)** - 与Tinybird无服务器ClickHouse平台交互
- <img height="12" width="12" src="https://unifai.network/favicon.ico" alt="UnifAI Logo" /> **[UnifAI](https://github.com/unifai-network/unifai-mcp-server)** - 使用[UnifAI Network](https://unifai.network)动态搜索和调用工具
- <img height="12" width="12" src="https://framerusercontent.com/images/plcQevjrOYnyriuGw90NfQBPoQ.jpg" alt="Unstructured Logo" /> **[Unstructured](https://github.com/Unstructured-IO/UNS-MCP)** - 在[Unstructured Platform](https://unstructured.io)中设置并与您的非结构化数据处理工作流交互
- **[Vectorize](https://github.com/vectorize-io/vectorize-mcp-server/)** - [Vectorize](https://vectorize.io) MCP服务器，用于高级检索、私人深度研究、任意格式到Markdown的文件提取和文本分块。
- <img height="12" width="12" src="https://verodat.io/assets/favicon-16x16.png" alt="Verodat Logo" /> **[Verodat](https://github.com/Verodat/verodat-mcp-server)** - 与Verodat AI就绪数据平台交互
- <img height="12" width="12" src="https://www.veyrax.com/favicon.ico" alt="VeyraX Logo" /> **[VeyraX](https://github.com/VeyraX/veyrax-mcp)** - 单一工具控制超过100个API集成和UI组件
- <img height="12" width="12" src="https://www.xero.com/favicon.ico" alt="Xero Logo" /> **[Xero](https://github.com/XeroAPI/xero-mcp-server)** - 使用我们的官方MCP服务器与您业务中的会计数据交互
- <img height="12" width="12" src="https://cdn.zapier.com/zapier/images/favicon.ico" alt="Zapier Logo" /> **[Zapier](https://zapier.com/mcp)** - 将您的AI代理即时连接到8000个应用程序。
- **[ZenML](https://github.com/zenml-io/mcp-zenml)** - 通过您的[ZenML](https://www.zenml.io) MCP服务器与您的MLOps和LLMOps管道交互
  
### 🌎 社区服务器

这是一个不断增长的社区开发和维护的服务器集合，展示了MCP在不同领域的各种应用。

> **注意：** 社区服务器是**未经测试的**，使用时需**自行承担风险**。它们与Anthropic无关，也不受其背书。
- **[Ableton Live](https://github.com/Simon-Kansara/ableton-live-mcp-server)** - 一个用于控制Ableton Live的MCP服务器。
- **[Airbnb](https://github.com/openbnb-org/mcp-server-airbnb)** - 提供搜索Airbnb和获取房源详情的工具。
- **[Algorand](https://github.com/GoPlausible/algorand-mcp)** - 一个全面的MCP服务器，提供40多种工具交互和60多种资源访问，以及与Algorand区块链交互的许多实用提示。
- **[Airflow](https://github.com/yangkyeongmo/mcp-server-apache-airflow)** - 一个连接到[Apache Airflow](https://airflow.apache.org/)的MCP服务器，使用官方Python客户端。
- **[Airtable](https://github.com/domdomegg/airtable-mcp-server)** - 对[Airtable](https://airtable.com/)数据库的读写访问，支持架构检查。
- **[Airtable](https://github.com/felores/airtable-mcp)** - Airtable模型上下文协议服务器。
- **[AlphaVantage](https://github.com/calvernaz/alphavantage)** - 用于股票市场数据API [AlphaVantage](https://www.alphavantage.co)的MCP服务器。
- **[Anki](https://github.com/scorzeth/anki-mcp-server)** - 一个用于与您的[Anki](https://apps.ankiweb.net)卡片和卡组交互的MCP服务器。
- **[Any Chat Completions](https://github.com/pyroprompts/any-chat-completions-mcp)** - 与任何兼容OpenAI SDK的聊天完成API交互，例如OpenAI、Perplexity、Groq、xAI等。
- **[Apple Calendar](https://github.com/Omar-v2/mcp-ical)** - 一个允许您通过自然语言与MacOS日历交互的MCP服务器，包括事件创建、修改、日程列表、查找空闲时间段等功能。
- **[ArangoDB](https://github.com/ravenwits/mcp-server-arangodb)** - 通过[ArangoDB](https://arangodb.com/)提供数据库交互功能的MCP服务器。
- **[Arduino](https://github.com/vishalmysore/choturobo)** - 一个使用Claude AI和Arduino（ESP32）实现AI驱动机器人技术的MCP服务器，用于现实世界的自动化和机器人交互。
- **[Atlassian](https://github.com/sooperset/mcp-atlassian)** - 与Atlassian云产品（Confluence和Jira）交互，包括搜索/阅读Confluence空间/页面、访问Jira问题和项目元数据。
- **[AWS](https://github.com/rishikavikondala/mcp-server-aws)** - 使用LLM对您的AWS资源执行操作。
- **[AWS Athena](https://github.com/lishenxydlgzs/aws-athena-mcp)** - 用于AWS Athena的MCP服务器，可在Glue Catalog上运行SQL查询。
- **[AWS Cost Explorer](https://github.com/aarora79/aws-cost-explorer-mcp-server)** - 通过检查各地区、服务、实例类型和基础模型的支出（包括Amazon Bedrock支出），使用此MCP服务器优化您的AWS支出（[演示视频](https://www.youtube.com/watch?v=WuVOmYLRFmI&feature=youtu.be)）。
- **[AWS Resources Operations](https://github.com/baryhuang/mcp-server-aws-resources-python)** - 运行生成的Python代码，安全地查询或修改boto3支持的任何AWS资源。
- **[AWS S3](https://github.com/aws-samples/sample-mcp-server-s3)** - 一个用于AWS S3的示例MCP服务器，可灵活地从S3获取对象，例如PDF文档。
- **[Azure ADX](https://github.com/pab1it0/adx-mcp-server)** - 查询和分析Azure Data Explorer数据库。
- **[Azure DevOps](https://github.com/Vortiago/mcp-azure-devops)** - 一个提供与Azure DevOps服务连接的MCP服务器，使AI助手能够查询和管理工作项。
- **[Baidu AI Search](https://github.com/baidubce/app-builder/tree/master/python/mcp_server/ai_search)** - 使用百度云的AI搜索进行网络搜索。
- **[Base Free USDC Transfer](https://github.com/magnetai/mcp-free-usdc-transfer)** - 使用Claude AI在[Base](https://base.org)上免费发送USDC！使用[Coinbase CDP](https://docs.cdp.coinbase.com/mpc-wallet/docs/welcome)构建。
* **[Basic Memory](https://github.com/basicmachines-co/basic-memory)** - 本地优先的知识管理系统，从Markdown文件中构建语义图，支持与LLM的跨会话持久内存。
- **[BigQuery](https://github.com/LucasHild/mcp-server-bigquery)** (by LucasHild) - 此服务器使LLM能够检查数据库架构并在BigQuery上执行查询。
- **[BigQuery](https://github.com/ergut/mcp-bigquery-server)** (by ergut) - Google BigQuery集成的服务器实现，支持直接访问和查询BigQuery数据库。
- **[Bing Web Search API](https://github.com/leehanchung/bing-search-mcp)** (by hanchunglee) - 微软Bing网络搜索API的服务器实现。
- **[Bitable MCP](https://github.com/lloydzhou/bitable-mcp)** (by lloydzhou) - MCP服务器通过模型上下文协议提供对Lark Bitable的访问，允许用户使用预定义工具与Bitable表格交互。
- **[Blender](https://github.com/ahujasid/blender-mcp)** (by ahujasid) - Blender集成，允许通过提示启用3D场景创建、建模和操作。
- **[browser-use](https://github.com/co-browser/browser-use-mcp-server)** (by co-browser) - 使用docker化的playwright + chromium + vnc的browser-use MCP服务器。支持stdio和可恢复的http。
- **[Bsc-mcp](https://github.com/TermiX-official/bsc-mcp)** - 第一个作为AI与BNB链桥梁的MCP服务器，使AI代理能够通过与BNB链无缝集成执行复杂的链上操作，包括转账、交换、启动、对任何代币进行安全检查等。
- **[Calculator](https://github.com/githejie/mcp-server-calculator)** - 此服务器使LLM能够使用计算器进行精确的数值计算。
- **[CFBD API](https://github.com/lenwood/cfbd-mcp-server)** - 用于[College Football Data API](https://collegefootballdata.com/)的MCP服务器。
- **[ChatMCP](https://github.com/AI-QL/chat-mcp)** – 一个开源跨平台GUI桌面应用程序，兼容Linux、macOS和Windows，支持与MCP服务器无缝交互，跨动态可选的LLM，由**[AIQL](https://github.com/AI-QL)**提供。
- **[ChatSum](https://github.com/mcpso/mcp-server-chatsum)** - 使用LLM查询和总结聊天消息，由[mcpso](https://mcp.so)提供。
- **[Chroma](https://github.com/privetin/chroma)** - 基于Chroma构建的向量数据库服务器，用于语义文档搜索和元数据过滤。
- **[ClaudePost](https://github.com/ZilongXue/claude-post)** - ClaudePost为Gmail提供无缝的电子邮件管理，提供安全的电子邮件搜索、阅读和发送功能。
- **[Cloudinary](https://github.com/felores/cloudinary-mcp-server)** - Cloudinary模型上下文协议服务器，用于将媒体上传到Cloudinary并获取媒体链接和详细信息。
- **[code-assistant](https://github.com/stippi/code-assistant)** - 一个编码助手MCP服务器，允许探索代码库并对代码进行更改。仅应与受信任的存储库一起使用（对提示注入的保护不足）。
- **[code-executor](https://github.com/bazinga012/mcp_code_executor)** - 一个允许LLM在指定Conda环境中执行Python代码的MCP服务器。
- **[code-sandbox-mcp](https://github.com/Automata-Labs-team/code-sandbox-mcp)** - 一个用于在Docker容器中创建安全代码沙箱环境以执行代码的MCP服务器。
- **[cognee-mcp](https://github.com/topoteretes/cognee/tree/main/cognee-mcp)** - 具有可定制摄取、数据处理和搜索功能的GraphRAG内存服务器。
- **[coin_api_mcp](https://github.com/longmans/coin_api_mcp)** - 提供对[coinmarketcap](https://coinmarketcap.com/)加密货币数据的访问。
- **[Contentful-mcp](https://github.com/ivo-toby/contentful-mcp)** - 在您的[Contentful](https://contentful.com)空间中读取、更新、删除、发布内容。
- **[crypto-feargreed-mcp](https://github.com/kukapay/crypto-feargreed-mcp)** - 提供实时和历史的加密恐惧与贪婪指数数据。
- **[cryptopanic-mcp-server](https://github.com/kukapay/cryptopanic-mcp-server)** - 通过CryptoPanic为AI代理提供最新的加密货币新闻。
- **[Dappier](https://github.com/DappierAI/dappier-mcp)** - 将LLM连接到实时、版权清晰的来自可信来源的专有数据。访问实时网络搜索、新闻、体育、金融数据、加密货币和优质出版商内容的专用模型。在[marketplace.dappier.com](https://marketplace.dappier.com/marketplace)探索数据模型。
- **[Databricks](https://github.com/JordiNeil/mcp-databricks-server)** - 允许LLM在Databricks账户中运行SQL查询，列出并获取作业执行详情。
- **[Data Exploration](https://github.com/reading-plus-ai/mcp-server-data-exploration)** - 用于基于.csv数据集的自主数据探索的MCP服务器，提供智能洞察，操作简单。注意：将在您的机器上执行任意Python代码，请谨慎使用！
- **[Dataset Viewer](https://github.com/privetin/dataset-viewer)** - 浏览和分析Hugging Face数据集，支持搜索、过滤、统计和数据导出功能。
- **[DBHub](https://github.com/bytebase/dbhub/)** - 通用的数据库MCP服务器，连接到MySQL、PostgreSQL、SQLite、DuckDB等。
- **[DeepSeek MCP Server](https://github.com/DMontgomery40/deepseek-mcp-server)** - 集成了DeepSeek高级语言模型的模型上下文协议服务器，此外还包括[其他实用API端点](https://github.com/DMontgomery40/deepseek-mcp-server?tab=readme-ov-file#features)。
- **[Deepseek_R1](https://github.com/66julienmartin/MCP-server-Deepseek_R1)** - 将Claude Desktop与DeepSeek语言模型（R1/V3）连接的模型上下文协议（MCP）服务器实现。
- **[deepseek-thinker-mcp](https://github.com/ruixingshi/deepseek-thinker-mcp)** - 为支持MCP的AI客户端（如Claude Desktop）提供Deepseek推理内容的MCP（模型上下文协议）提供者。支持从Deepseek API服务或本地Ollama服务器访问Deepseek的思维过程。
- **[Descope](https://github.com/descope-sample-apps/descope-mcp-server)** - 一个与[Descope](https://descope.com)集成以搜索审计日志、管理用户等的MCP服务器。
- **[DevRev](https://github.com/kpsunil97/devrev-mcp-server)** - 一个与DevRev API集成的MCP服务器，可搜索您的DevRev知识图谱，对象可从[此处列出的不同来源](https://devrev.ai/docs/import#available-sources)导入。
- **[Dicom](https://github.com/ChristianHinge/dicom-mcp)** - 一个用于查询和检索医学图像以及解析和读取dicom封装文档（pdf等）的MCP服务器。
- **[Dify](https://github.com/YanxingLiu/dify-mcp-server)** - 一个用于dify工作流的简单MCP服务器实现。
- **[Discord](https://github.com/v-3/discordmcp)** - 一个通过机器人连接到Discord公会的MCP服务器，可在频道中读写消息。
- **[Discord](https://github.com/SaseQ/discord-mcp)** - 一个通过机器人连接到Discord的MCP服务器，提供与Discord的全面集成。
- **[Discourse](https://github.com/AshDevFr/discourse-mcp-server)** - 一个用于在Discourse论坛上搜索帖子内容的MCP服务器。
- **[Docker](https://github.com/ckreiling/mcp-server-docker)** - 与Docker集成以管理容器、镜像、卷和网络。
- **[Drupal](https://github.com/Omedia/mcp-server-drupal)** - 使用STDIO传输层与[Drupal](https://www.drupal.org/project/mcp)交互的服务器。
- **[dune-analytics-mcp](https://github.com/kukapay/dune-analytics-mcp)** - 将Dune Analytics数据桥接到AI代理的MCP服务器。
- **[Elasticsearch](https://github.com/cr7258/elasticsearch-mcp-server)** - 提供Elasticsearch交互的MCP服务器实现。
- **[ElevenLabs](https://github.com/mamertofabian/elevenlabs-mcp-server)** - 一个与ElevenLabs文本转语音API集成的服务器，能够生成多声部的完整配音。
- **[Ergo Blockchain MCP](https://github.com/marctheshark3/ergo-mcp)** - 一个集成Ergo区块链节点和Explorer API的MCP服务器，用于检查地址余额、分析交易、查看交易历史、对地址进行取证分析、搜索代币和监控网络状态。
- **[Eunomia](https://github.com/whataboutyou-ai/eunomia-MCP-server)** - Eunomia框架的扩展，将Eunomia工具与MCP服务器连接。
- **[EVM MCP Server](https://github.com/mcpdotdirect/evm-mcp-server)** - 为30多个EVM网络提供全面的区块链服务，支持原生代币、ERC20、NFT、智能合约、交易和ENS解析。
- **[Everything Search](https://github.com/mamertofabian/mcp-everything-search)** - 跨Windows（使用[Everything SDK](https://www.voidtools.com/support/everything/sdk/)）、macOS（使用mdfind命令）和Linux（使用locate/plocate命令）的快速文件搜索功能。
- **[Excel](https://github.com/haris-musa/excel-mcp-server)** - Excel操作，包括数据读写、工作表管理、格式设置、图表和数据透视表。
- **[Fantasy PL](https://github.com/rishijatia/fantasy-pl-mcp)** - 为您的编码代理提供最新的Fantasy Premier League数据的直接访问。
- **[fastn.ai – Unified API MCP Server](https://github.com/fastnai/mcp-fastn)** - 一个远程动态MCP服务器，带有统一API，连接到1000多种工具、操作和工作流，具有内置认证和监控功能。
- **[Fetch](https://github.com/zcaceres/fetch-mcp)** - 一个灵活获取HTML、JSON、Markdown或纯文本的服务器。
- **[Fingertip](https://github.com/fingertip-com/fingertip-mcp)** - 用于Fingertip.com的MCP服务器，可搜索和创建新站点。
- **[Figma](https://github.com/GLips/Figma-Context-MCP)** - 为您的编码代理提供对Figma文件数据的直接访问，帮助其一次性实现设计。
- **[Firebase](https://github.com/gannonh/firebase-mcp)** - 与Firebase服务交互的服务器，包括Firebase身份验证、Firestore和Firebase存储。
- **[FireCrawl](https://github.com/vrknetha/mcp-server-firecrawl)** - 高级网页抓取，支持JavaScript渲染、PDF支持和智能速率限制。
- **[FlightRadar24](https://github.com/sunsetcoder/flightradar24-mcp-server)** - 一个Claude Desktop MCP服务器，帮助您使用Flightradar24数据实时跟踪航班。
- **[Ghost](https://github.com/MFYDev/ghost-mcp)** - 一个用于通过LLM界面（如Claude）与Ghost CMS交互的模型上下文协议（MCP）服务器。
- **[Github Actions](https://github.com/ko1ynnky/github-actions-mcp-server)** - 一个用于与Github Actions交互的模型上下文协议（MCP）服务器。
- **[Glean](https://github.com/longyi1207/glean-mcp-server)** - 一个使用Glean API进行搜索和聊天的服务器。
- **[Gmail](https://github.com/GongRzhe/Gmail-MCP-Server)** - 一个在Claude Desktop中集成Gmail的模型上下文协议（MCP）服务器，支持自动身份验证。
- **[Gmail Headless](https://github.com/baryhuang/mcp-headless-gmail)** - 一个可远程托管的MCP服务器，无需本地凭据或文件系统设置即可获取和发送Gmail消息。
- **[Goal Story](https://github.com/hichana/goalstory-mcp)** - 一个用于个人和职业发展的目标追踪和可视化工具。
- **[GOAT](https://github.com/goat-sdk/goat/tree/main/typescript/examples/by-framework/model-context-protocol)** - 在包括Ethereum、Solana和Base在内的任何区块链上运行200多种链上操作。
- **[Godot](https://github.com/Coding-Solo/godot-mcp)** - 一个提供Godot引擎全面集成的MCP服务器，支持项目编辑、调试和场景管理。
- **[Golang Filesystem Server](https://github.com/mark3labs/mcp-filesystem-server)** - 使用Go构建的具有可配置访问控制的安全文件操作！
- **[Goodnews](https://github.com/VectorInstitute/mcp-goodnews)** - 一个提供精选积极和振奋人心的新闻故事的简单MCP服务器。
- **[Google Calendar](https://github.com/v-3/google-calendar)** - 与Google Calendar集成，检查日程、查找时间并添加/删除事件。
- **[Google Calendar](https://github.com/nspady/google-calendar-mcp)** - 用于管理Google日历事件的Google Calendar MCP服务器。还支持按标题和位置等属性搜索事件。
- **[Google Custom Search](https://github.com/adenot/mcp-google-search)** - 通过Google自定义搜索API提供Google搜索结果。
- **[Google Tasks](https://github.com/zcaceres/gtasks-mcp)** - Google Tasks API模型上下文协议服务器。
- **[GraphQL Schema](https://github.com/hannesj/mcp-graphql-schema)** - 允许LLM探索大型GraphQL架构而不增加上下文负担。
- **[HDW LinkedIn](https://github.com/horizondatawave/hdw-mcp-server)** - 通过[HorizonDataWave.ai](https://horizondatawave.ai/)访问个人资料数据和管理用户账户。
- **[Heurist Mesh Agent](https://github.com/heurist-network/heurist-mesh-mcp-server)** - 通过[Heurist Mesh网络](https://github.com/heurist-network/heurist-agent-framework/tree/main/mesh)访问专用的web3 AI代理，用于区块链分析、智能合约安全、代币指标和区块链交互。
- **[Holaspirit](https://github.com/syucream/holaspirit-mcp-server)** - 与[Holaspirit](https://www.holaspirit.com/)交互。
- **[Home Assistant](https://github.com/tevonsb/homeassistant-mcp)** - 与[Home Assistant](https://www.home-assistant.io/)交互，包括查看和控制灯光、开关、传感器和其他所有Home Assistant实体。
- **[Home Assistant](https://github.com/voska/hass-mcp)** - 为Home Assistant提供Docker就绪的MCP服务器，支持实体管理、域摘要、自动化支持和引导对话。包括易于安装的预构建容器镜像。
- **[HubSpot](https://github.com/buryhuang/mcp-hubspot)** - HubSpot CRM集成，用于管理联系人和公司。通过Claude聊天直接创建和检索CRM数据。
- **[HuggingFace Spaces](https://github.com/evalstate/mcp-hfspace)** - 用于HuggingFace Spaces的服务器，支持开源图像、音频、文本模型等。Claude Desktop模式便于集成。
- **[Hyperliquid](https://github.com/mektigboy/server-hyperliquid)** - 一个集成了Hyperliquid SDK用于交易所数据的MCP服务器实现。
- **[iFlytek Workflow](https://github.com/iflytek/ifly-workflow-mcp-server)** - 通过MCP服务器连接到iFlytek Workflow并运行您自己的代理。
- **[Image Generation](https://github.com/GongRzhe/Image-Generation-MCP-Server)** - 此MCP服务器使用Replicate Flux模型提供图像生成功能。
- **[InfluxDB](https://github.com/idoru/influxdb-mcp-server)** - 对InfluxDB OSS API v2运行查询。
- **[Inoyu](https://github.com/sergehuber/inoyu-mcp-unomi-server)** - 与Apache Unomi CDP客户数据平台交互，以检索和更新客户档案。
- **[Intercom](https://github.com/raoulbia-ai/mcp-server-for-intercom)** - 一个符合MCP标准的服务器，用于从Intercom检索客户支持票据。此工具使Claude Desktop和Cline等AI助手能够访问和分析您的Intercom支持票据。
- **[iTerm MCP](https://github.com/ferrislucas/iterm-mcp)** - 与macOS的iTerm2终端仿真器集成，使LLM能够执行和监控终端命令。
- **[JavaFX](https://github.com/mcpso/mcp-server-javafx)** - 使用JavaFX画布进行绘图。
- **[JDBC](https://github.com/quarkiverse/quarkus-mcp-servers/tree/main/jdbc)** - 连接到任何兼容JDBC的数据库并进行查询、插入、更新、删除等操作。支持MySQL、PostgreSQL、Oracle、SQL Server、SQLite和[更多](https://github.com/quarkiverse/quarkus-mcp-servers/tree/main/jdbc#supported-jdbc-variants)。
- **[JSON](https://github.com/GongRzhe/JSON-MCP-Server)** - 具有使用JSONPath语法的高级查询功能的JSON处理和加工服务器，支持数组、字符串、数字和日期操作。
- **[KiCad MCP](https://github.com/lamaalrajih/kicad-mcp)** - 用于Mac、Windows和Linux上的KiCad的MCP服务器。
- **[Keycloak MCP](https://github.com/ChristophEnglisch/keycloak-model-context-protocol)** - 此MCP服务器支持通过自然语言与Keycloak交互进行用户和领域管理，包括创建、删除和列出用户和领域。
- **[Kibela](https://github.com/kiwamizamurai/mcp-kibela-server)** (by kiwamizamurai) - 与Kibela API交互。
- **[kintone](https://github.com/macrat/mcp-server-kintone)** - 通过LLM工具管理[kintone](https://kintone.com)中的记录和应用。
- **[Kong Konnect](https://github.com/Kong/mcp-konnect)** - 一个用于与Kong Konnect API交互的模型上下文协议（MCP）服务器，允许AI助手查询和分析Kong Gateway配置、流量和分析。
- **[Kubernetes](https://github.com/Flux159/mcp-server-kubernetes)** - 连接到Kubernetes集群并管理pod、部署和服务。
- **[Kubernetes and OpenShift](https://github.com/manusa/kubernetes-mcp-server)** - 一个功能强大的Kubernetes MCP服务器，额外支持OpenShift。除了为任何Kubernetes资源提供CRUD操作外，此服务器还提供与您的集群交互的专用工具。
- **[Langflow-DOC-QA-SERVER](https://github.com/GongRzhe/Langflow-DOC-QA-SERVER)** - 一个由Langflow支持的文档问答模型上下文协议服务器。它通过提供一个简单的接口来查询Langflow后端的文档，展示了MCP核心概念。
- **[Lightdash](https://github.com/syucream/lightdash-mcp-server)** - 与[Lightdash](https://www.lightdash.com/)交互，一个BI工具。
- **[Linear](https://github.com/jerhadf/linear-mcp-server)** - 允许LLM与Linear的API交互进行项目管理，包括搜索、创建和更新问题。
- **[Linear (Go)](https://github.com/geropl/linear-mcp-go)** - 允许LLM通过单一静态二进制文件与Linear的API交互。
- **[LINE](https://github.com/amornpan/py-mcp-line)** (by amornpan) - LINE Bot集成的实现，使语言模型能够通过标准化界面读取和分析LINE对话。具有异步操作、全面日志记录、Webhook事件处理和对各种消息类型的支持。
- **[LlamaCloud](https://github.com/run-llama/mcp-server-llamacloud)** (by marcusschiesser) - 集成存储在[LlamaCloud](https://cloud.llamaindex.ai/)上的托管索引中的数据。
- **[llm-context](https://github.com/cyberchitta/llm-context.py)** - 提供具有可配置文件的存储库打包MCP工具，指定文件包含/排除模式和可选提示。
- **[mac-messages-mcp](https://github.com/carterlasalle/mac_messages_mcp)** - 一个通过模型上下文协议（MCP）安全接口与您的iMessage数据库交互的MCP服务器，允许LLM查询和分析iMessage对话。包括强大的电话号码验证、附件处理、联系人管理、群聊处理以及发送和接收消息的全面支持。
- **[MariaDB](https://github.com/abel9851/mcp-server-mariadb)** - 使用Python实现的MariaDB数据库集成，具有可配置的访问控制。
- **[Maton](https://github.com/maton-ai/agent-toolkit/tree/main/modelcontextprotocol)** - 连接到您的SaaS工具，如HubSpot、Salesforce等。
- **[MCP Compass](https://github.com/liuyoshio/mcp-compass)** - 为您的需求建议合适的MCP服务器。
- **[MCP Create](https://github.com/tesla0225/mcp-create)** - 一个动态MCP服务器管理服务，可即时创建、运行和管理模型上下文协议服务器。
- **[MCP Installer](https://github.com/anaisbetts/mcp-installer)** - 此服务器是一个为您安装其他MCP服务器的服务器。
- **[mcp-k8s-go](https://github.com/strowk/mcp-k8s-go)** - 基于Golang的Kubernetes服务器，用于MCP浏览pod及其日志、事件、命名空间等。构建为可扩展。
- **[mcp-local-rag](https://github.com/nkapila6/mcp-local-rag)** - “原始”类似RAG的网络搜索模型上下文协议（MCP）服务器，使用Google的MediaPipe Text Embedder和DuckDuckGo Search在本地运行。✨无需API✨。
- **[mcp-proxy](https://github.com/sparfenyuk/mcp-proxy)** - 连接到运行在SSE传输上的MCP服务器，或将stdio服务器暴露为SSE服务器。
- **[mem0-mcp](https://github.com/mem0ai/mem0-mcp)** - 一个用于Mem0的模型上下文协议服务器，有助于管理编码偏好。
- **[MSSQL](https://github.com/aekanun2020/mcp-server/)** - MSSQL数据库集成，具有可配置的访问控制和架构检查。
- **[MSSQL](https://github.com/JexinSam/mssql_mcp_server)** (by jexin) - Python中的MSSQL数据库MCP服务器。
- **[MSSQL-Python](https://github.com/amornpan/py-mcp-mssql)** (by amornpan) - 一个只读的Python实现，用于MSSQL数据库访问，具有增强的安全功能、可配置的访问控制和架构检查功能。专注于通过Python生态系统进行安全的数据库交互。
- **[MSSQL-MCP](https://github.com/daobataotie/mssql-mcp)** (by daobataotie) - 参考官方网站的SQLite MCP进行修改以适应MSSQL的MSSQL MCP。
- **[Markdownify](https://github.com/zcaceres/mcp-markdownify-server)** - 将几乎任何内容转换为Markdown的MCP（PPTX、HTML、PDF、YouTube字幕等）。
- **[Mindmap](https://github.com/YuChenSSR/mindmap-mcp-server)** (by YuChenSSR) - 一个从包含Markdown代码的输入生成思维导图的服务器。
- **[Minima](https://github.com/dmayboroda/minima)** - 用于本地文件RAG的MCP服务器。
- **[Mobile MCP](https://github.com/mobile-next/mobile-mcp)** (by Mobile Next) - 用于移动设备（iOS/Android）自动化、应用抓取和开发的MCP服务器，使用物理设备或模拟器/仿真器。
- **[MongoDB](https://github.com/kiliczsh/mcp-mongo-server)** - 一个用于MongoDB的模型上下文协议服务器。
- **[MongoDB Lens](https://github.com/furey/mongodb-lens)** - 为MongoDB数据库提供全面功能的MCP服务器。
- **[Monday.com](https://github.com/sakce/mcp-server-monday)** - 与Monday.com看板和项目交互的MCP服务器。
- **[Multicluster-MCP-Sever](https://github.com/yanmxa/multicluster-mcp-server)** - GenAI系统与多个Kubernetes集群交互的网关。
- **[MySQL](https://github.com/benborla/mcp-server-mysql)** (by benborla) - 使用NodeJS实现的MySQL数据库集成，具有可配置的访问控制和架构检查。
- **[MySQL](https://github.com/designcomputer/mysql_mcp_server)** (by DesignComputer) - 使用Python实现的MySQL数据库集成，具有可配置的访问控制和架构检查。
- **[n8n](https://github.com/leonardsellem/n8n-mcp-server)** - 此MCP服务器为AI助手提供管理n8n工作流和执行的工具和资源，包括列出、创建、更新和删除工作流，以及监控其执行状态。
- **[NASA](https://github.com/ProgramComputer/NASA-MCP-server)** (by ProgramComputer) - 访问NASA数据源的统一网关，包括但不限于APOD、NEO、EPIC、GIBS。
- **[National Parks](https://github.com/KyrieTangSheng/mcp-server-nationalparks)** - 该服务器提供美国国家公园的最新信息，包括公园详情、警报、游客中心、露营地、徒步 trail 和活动。
- **[NAVER](https://github.com/pfldy2850/py-mcp-naver)** (by pfldy2850) - 此MCP服务器提供与各种Naver服务交互的工具，例如搜索博客、新闻、书籍等。
- **[NS Travel Information](https://github.com/r-huijts/ns-mcp-server)** - 通过官方NS API访问荷兰铁路（NS）的实时火车旅行信息和中断情况。
- **[Neo4j](https://github.com/da-okazaki/mcp-neo4j-server)** - 一个与Neo4j图形数据库交互的社区构建服务器。
- **[Neovim](https://github.com/bigcodegen/mcp-neovim-server)** - 为您的Neovim会话提供的MCP服务器。
- **[Notion](https://github.com/suekou/mcp-notion-server)** (by suekou) - 与Notion API交互。
- **[Notion](https://github.com/v-3/notion-server)** (by v-3) - Notion MCP集成。通过Claude聊天搜索、读取、更新和创建页面。
- **[ntfy-mcp](https://github.com/teddyzxcv/ntfy-mcp)** (by teddyzxcv) - 通过使用ntfy在手机上发送通知来保持您了解情况的MCP服务器。
- **[oatpp-mcp](https://github.com/oatpp/oatpp-mcp)** - 用于Oat++的C++ MCP集成。使用[Oat++](https://oatpp.io)构建MCP服务器。
- **[Obsidian Markdown Notes](https://github.com/calclavia/mcp-obsidian)** - 读取和搜索您的Obsidian vault或任何包含Markdown笔记的目录。
- **[obsidian-mcp](https://github.com/StevenStavrakis/obsidian-mcp)** - (by Steven Stavrakis) 一个用于Obsidian.md的MCP服务器，提供搜索、读取、写入和组织笔记的工具。
- **[OceanBase](https://github.com/yuanoOo/oceanbase_mcp_server)** - (by yuanoOo) 一个使与OceanBase数据库安全交互的模型上下文协议（MCP）服务器。
- **[Okta](https://github.com/kapilduraphe/okta-mcp-server)** - 与Okta API交互。
- **[OneNote](https://github.com/rajvirtual/MCP-Servers/tree/master/onenote)** - (by Rajesh Vijay) 一个使用Microsoft Graph API连接到Microsoft OneNote的MCP服务器。从OneNote读取笔记本、部分和页面，创建新的笔记本、部分和页面。
- **[OpenAI WebSearch MCP](https://github.com/ConechoAI/openai-websearch-mcp)** - 这是一个基于Python的MCP服务器，提供OpenAI的`web_search`内置工具。
- **[OpenAPI](https://github.com/snaggle-ai/openapi-mcp-server)** - 与[OpenAPI](https://www.openapis.org/) API交互。
- **[OpenAPI AnyApi](https://github.com/baryhuang/mcp-server-any-openapi)** - 使用内置的端点语义搜索与大型[OpenAPI](https://www.openapis.org/)文档交互。允许自定义MCP服务器前缀。
- **[OpenAPI Schema](https://github.com/hannesj/mcp-openapi-schema)** - 允许LLM探索大型[OpenAPI](https://www.openapis.org/)架构而不增加上下文负担。
- **[OpenCTI](https://github.com/Spathodea-Network/opencti-mcp)** - 与OpenCTI平台交互以检索威胁情报数据，包括报告、指标、恶意软件和威胁行为者。
- **[OpenDota](https://github.com/asusevski/opendota-mcp-server)** - 与OpenDota API交互以检索Dota 2比赛数据、玩家统计等。
- **[OpenRPC](https://github.com/shanejonas/openrpc-mpc-server)** - 通过[OpenRPC](https://open-rpc.org)与JSON-RPC API交互和发现。
- **[Open Strategy Partners Marketing Tools](https://github.com/open-strategy-partners/osp_marketing_tools)** - 用于产品营销的内容编辑代码、价值图和定位工具。
- **[Pandoc](https://github.com/vivekVells/mcp-pandoc)** - 使用Pandoc实现无缝文档格式转换的MCP服务器，支持Markdown、HTML、PDF、DOCX（.docx）、csv等。
- **[PIF](https://github.com/hungryrobot1/MCP-PIF)** - 一个个人智能框架（PIF），提供文件操作、结构化推理和基于日志的文档工具，以支持跨会话的连续性和不断发展的人机协作。
- **[Pinecone](https://github.com/sirmews/mcp-pinecone)** - 用于搜索和上传记录到Pinecone的MCP服务器。允许利用Pinecone的Inference API实现简单的RAG功能。
- **[Placid.app](https://github.com/felores/placid-mcp-server)** - 使用Placid.app模板生成图像和视频创意。
- **[Playwright](https://github.com/executeautomation/mcp-playwright)** - 此MCP服务器将帮助您使用Playwright运行浏览器自动化和网页抓取。
- **[Postman](https://github.com/shannonlal/mcp-postman)** - 用于通过Newman本地运行Postman集合的MCP服务器。允许简单执行Postman服务器并返回集合是否通过所有测试的结果。
- **[Productboard](https://github.com/kenjihikmatullah/productboard-mcp)** - 通过MCP将Productboard API集成到代理工作流中。
- **[Prometheus](https://github.com/pab1it0/prometheus-mcp-server)** - 查询和分析Prometheus - 开源监控系统。
- **[Pulumi](https://github.com/dogukanakkaya/pulumi-mcp-server)** - 与Pulumi API交互的MCP服务器，创建和列出堆栈。
- **[Pushover](https://github.com/ashiknesin/pushover-mcp)** - 使用[Pushover.net](https://pushover.net/)向您的设备发送即时通知。
- **[QGIS](https://github.com/jjsantos01/qgis_mcp)** - 通过MCP将QGIS连接到Claude AI。此集成支持通过提示辅助项目创建、加载图层、执行代码等。
- **[QuickChart](https://github.com/GongRzhe/Quickchart-MCP-Server)** - 一个使用QuickChart.io生成图表的模型上下文协议服务器。
- **[Qwen_Max](https://github.com/66julienmartin/MCP-server-Qwen_Max)** - Qwen模型的模型上下文协议（MCP）服务器实现。
- **[RabbitMQ](https://github.com/kenliao94/mcp-server-rabbitmq)** - 与RabbitMQ交互以发布和消费消息的MCP服务器。
- **[RAG Web Browser](https://github.com/apify/mcp-server-rag-web-browser)** - Apify的开源RAG Web Browser [Actor](https://apify.com/apify/rag-web-browser)的MCP服务器，用于执行网络搜索、抓取URL并以Markdown格式返回内容。
- **[Reaper](https://github.com/dschuler36/reaper-mcp-server)** - 与您的[Reaper](https://www.reaper.fm/)（数字音频工作站）项目交互。
- **[Redis](https://github.com/GongRzhe/REDIS-MCP-Server)** - Redis数据库操作和缓存微服务服务器，支持键值操作、过期管理以及基于模式的键列出。
- **[Redis](https://github.com/prajwalnayak7/mcp-server-redis)** - 与Redis服务器、AWS Memory DB等交互的MCP服务器，用于缓存或其他适合内存和键值存储的用例。
- **[Rememberizer AI](https://github.com/skydeckai/mcp-server-rememberizer)** - 一个专为与Rememberizer数据源交互设计的MCP服务器，促进增强的知识检索。
- **[Replicate](https://github.com/deepfates/mcp-replicate)** - 通过简单的基于工具的界面在Replicate上搜索、运行和管理机器学习模型。浏览模型、创建预测、跟踪其状态并处理生成的图像。
- **[Rquest](https://github.com/xxxbrian/mcp-rquest)** - 一个提供具有准确TLS/JA3/JA4指纹的真实浏览器类HTTP请求功能的MCP服务器，用于绕过反机器人措施。
- **[Rijksmuseum](https://github.com/r-huijts/rijksmuseum-mcp)** - 与Rijksmuseum API交互，搜索艺术品、检索艺术品详情、访问图像瓦片并探索用户收藏。
- **[Salesforce MCP](https://github.com/smn2gnt/MCP-Salesforce)** - 与Salesforce数据和元数据交互。
- **[Scholarly](https://github.com/adityak74/mcp-scholarly)** - 一个用于搜索学术和学术文章的MCP服务器。
- **[scrapling-fetch](https://github.com/cyberchitta/scrapling-fetch-mcp)** - 从受机器人保护的网站访问文本内容。使用Scrapling从具有反自动化措施的网站获取HTML/Markdown。
- **[SearXNG](https://github.com/ihor-sokoliuk/mcp-searxng)** - [SearXNG](https://docs.searxng.org)的模型上下文协议服务器。
- **[ServiceNow](https://github.com/osomai/servicenow-mcp)** - 一个与ServiceNow实例交互的MCP服务器。
- **[Shopify](https://github.com/GeLi2001/shopify-mcp)** - 与Shopify API交互的MCP，包括订单、产品、客户等。
- **[Siri Shortcuts](https://github.com/dvcrn/mcp-server-siri-shortcuts)** - 与macOS上的Siri Shortcuts交互的MCP。将所有Shortcuts暴露为MCP工具。
- **[Snowflake](https://github.com/isaacwasserman/mcp-snowflake-server)** - 此MCP服务器使LLM能够与Snowflake数据库交互，允许安全和受控的数据操作。
- **[Solana Agent Kit](https://github.com/sendaifun/solana-agent-kit/tree/main/examples/agent-kit-mcp-server)** - 此MCP服务器使LLM能够通过SendAI的Solana Agent Kit与Solana区块链交互，支持40多种协议操作且不断增加。
- **[Spotify](https://github.com/varunneal/spotify-mcp)** - 此MCP允许LLM播放和使用Spotify。
- **[Starwind UI](https://github.com/Boston343/starwind-ui-mcp/)** - 此MCP提供相关命令、文档和其他信息，使LLM能够充分利用Starwind UI的开源Astro组件。
- **[Stripe](https://github.com/atharvagupta2003/mcp-stripe)** - 此MCP允许与Stripe集成以处理付款、客户和退款。
- **[TMDB](https://github.com/Laksh-star/mcp-server-tmdb)** - 此MCP服务器与The Movie Database（TMDB）API集成，提供电影信息、搜索功能和推荐。
- **[Tavily search](https://github.com/RamXX/mcp-tavily)** - Tavily搜索和新闻API的MCP服务器，支持明确的站点包含/排除。
- **[Telegram](https://github.com/chigwell/telegram-mcp)** - 一个通过Telethon集成提供Telegram分页聊天读取、消息检索和消息发送功能的MCP服务器。
- **[Terminal-Control](https://github.com/GongRzhe/terminal-controller-mcp)** - 一个通过标准化界面启用安全终端命令执行、目录导航和文件系统操作的MCP服务器。
- **[TFT-Match-Analyzer](https://github.com/GeLi2001/tft-mcp-server)** - 用于团队战斗策略（Teamfight Tactics）比赛历史和比赛详情获取的MCP服务器，为用户提供每场比赛的详细上下文。
- **[Ticketmaster](https://github.com/delorenj/mcp-server-ticketmaster)** - 通过Ticketmaster Discovery API搜索活动、场地和景点。
- **[Todoist](https://github.com/abhiz123/todoist-mcp-server)** - 与Todoist交互以管理您的任务。
- **[Typesense](https://github.com/suhail-ak-s/mcp-typesense-server)** - 一个为AI模型提供Typesense搜索功能的模型上下文协议（MCP）服务器实现。此服务器使LLM能够发现、搜索和分析存储在Typesense集合中的数据。
- **[Travel Planner](https://github.com/GongRzhe/TRAVEL-PLANNER-MCP-Server)** - 旅行规划和行程管理服务器，与Google Maps API集成，用于位置搜索、地点详情和路线计算。
- **[Unity Catalog](https://github.com/ognis1205/mcp-server-unitycatalog)** - 一个使LLM能够与Unity Catalog AI交互的MCP服务器，支持对Unity Catalog函数的CRUD操作并将其作为MCP工具执行。
- **[Unity3d Game Engine](https://github.com/CoderGamester/mcp-unity)** - 一个使LLM能够与Unity3d游戏引擎交互的MCP服务器，支持访问各种Unity编辑器引擎工具（例如控制台日志、测试运行器日志、编辑器函数、层级状态等）并将其作为MCP工具执行或收集为资源。
- **[Unity Integration (Advanced)](https://github.com/quazaai/UnityMCPIntegration)** - 高级Unity3d游戏引擎MCP，支持直接在Unity内执行任何与编辑器相关的代码、获取日志、获取编辑器状态以及允许访问项目的文件，使其在脚本编辑或资产创建中更加实用。
- **[Vega-Lite](https://github.com/isaacwasserman/mcp-vegalite-server)** - 使用VegaLite格式和渲染器从获取的数据生成可视化。
- **[Video Editor](https://github.com/burningion/video-editing-mcp)** - 一个用于添加、编辑和搜索视频的模型上下文协议服务器，与[Video Jungle](https://www.video-jungle.com/)配合使用。
- **[Virtual location (Google Street View,etc.)](https://github.com/mfukushim/map-traveler-mcp)** - 集成Google Map、Google Street View、PixAI、Stability.ai、ComfyUI API和Bluesky，在LLM中提供虚拟位置模拟（使用Effect.ts编写）。
- **[VolcEngine TOS](https://github.com/dinghuazhou/sample-mcp-server-tos)** - 一个用于VolcEngine TOS的示例MCP服务器，可灵活地从TOS获取对象。
- **[Wanaku MCP Router](https://github.com/wanaku-ai/wanaku/)** - Wanaku MCP路由器是一个基于SSE的MCP服务器，提供可扩展的路由引擎，允许将您的企业系统与AI代理集成。
- **[Webflow](https://github.com/kapilduraphe/webflow-mcp-server)** - 与Webflow API交互。
- **[whale-tracker-mcp](https://github.com/kukapay/whale-tracker-mcp)** - 一个用于跟踪加密货币鲸鱼交易的MCP服务器。
- **[Whois MCP](https://github.com/bharathvaj-ganesan/whois-mcp)** - 一个对域名、IP、ASN和TLD执行whois查询的MCP服务器。
- **[Wikidata MCP](https://github.com/zzaebok/mcp-wikidata)** - 与Wikidata交互的Wikidata MCP服务器，通过搜索标识符、提取元数据和执行SPARQL查询。
- **[WildFly MCP](https://github.com/wildfly-extras/wildfly-mcp)** - WildFly MCP服务器，使LLM能够与运行中的WildFly服务器交互（检索指标、日志、调用操作等）。
- **[Windows CLI](https://github.com/SimonB97/win-cli-mcp-server)** - 用于Windows系统上安全命令行交互的MCP服务器，支持对PowerShell、CMD和Git Bash shell的受控访问。
- **[World Bank data API](https://github.com/anshumax/world_bank_mcp_server)** - 一个获取世界银行数据API中可用数据指标的服务器。
- **[X (Twitter)](https://github.com/EnesCinr/twitter-mcp)** (by EnesCinr) - 与Twitter API交互。发布推文并按查询搜索推文。
- **[X (Twitter)](https://github.com/vidhupv/x-mcp)** (by vidhupv) - 通过Claude聊天直接创建、管理和发布X/Twitter帖子。
- **[xcodebuild](https://github.com/ShenghaiWang/xcodebuild)** - 🍎 构建iOS Xcode工作区/项目并将错误反馈给LLM。
- **[Xero-mcp-server](https://github.com/john-zhang-dev/xero-mcp)** - 使客户能够与Xero系统交互，以简化会计、发票和业务操作。
- **[XiYan](https://github.com/XGenerationLab/xiyan_mcp_server)** - 🗄️ 一个支持使用自然语言查询从数据库获取数据的MCP服务器，由XiyanSQL作为文本转SQL的LLM提供支持。
- **[XMind](https://github.com/apeyroux/mcp-xmind)** - 读取和搜索包含XMind文件的XMind目录。
- **[YouTube](https://github.com/ZubeidHendricks/youtube-mcp-server)** - 全面的YouTube API集成，用于视频管理、短视频创建和分析。
  
## 📚 框架

这些是高级框架，可以更轻松地构建MCP服务器或客户端。

### 用于服务器

* **[EasyMCP](https://github.com/zcaceres/easy-mcp/)** (TypeScript)
- **[FastAPI转MCP自动生成器](https://github.com/tadata-org/fastapi_mcp)** – 一个零配置工具，用于自动将FastAPI端点暴露为MCP工具，由**[Tadata](https://tadata.com/)**提供
* **[FastMCP](https://github.com/punkpeye/fastmcp)** (TypeScript)
* **[Foxy Contexts](https://github.com/strowk/foxy-contexts)** – 一个用于在Golang中构建MCP服务器的库，由**[strowk](https://github.com/strowk)**提供
* **[Higress MCP服务器托管](https://github.com/alibaba/higress/tree/main/plugins/wasm-go/mcp-servers)** - 通过使用wasm插件扩展API网关（基于Envoy）来托管MCP服务器的解决方案。
* **[MCP-Framework](https://mcp-framework.com)** 使用TypeScript优雅而快速地构建MCP服务器。附带CLI工具，通过`mcp create app`创建项目。在不到5分钟内开始您的第一个服务器，由**[Alex Andru](https://github.com/QuantGeekDev)**提供
* **[Quarkus MCP服务器SDK](https://github.com/quarkiverse/quarkus-mcp-server)** (Java)
* **[模板MCP服务器](https://github.com/mcpdotdirect/template-mcp-server)** - 一个CLI工具，用于创建新的模型上下文协议服务器项目，支持TypeScript、双重传输选项和可扩展结构

### 用于客户端

* **[codemirror-mcp](https://github.com/marimo-team/codemirror-mcp)** - CodeMirror扩展，实现了模型上下文协议（MCP），用于资源提及和提示命令

## 📚 资源

关于MCP的附加资源。

- **[AiMCP](https://www.aimcp.info)** - 一系列MCP客户端和服务器，帮助找到合适的MCP工具，由**[Hekmon](https://github.com/hekmon8)**提供
- **[Awesome Crypto MCP Servers by badkk](https://github.com/badkk/awesome-crypto-mcp-servers)** - 由**[Luke Fan](https://github.com/badkk)**整理的MCP服务器精选列表
- **[Awesome MCP Servers by appcypher](https://github.com/appcypher/awesome-mcp-servers)** - 由**[Stephen Akinyemi](https://github.com/appcypher)**整理的MCP服务器精选列表
- **[Awesome MCP Servers by punkpeye](https://github.com/punkpeye/awesome-mcp-servers)** (**[网站](https://glama.ai/mcp/servers)**) - 由**[Frank Fiegel](https://github.com/punkpeye)**整理的MCP服务器精选列表
- **[Awesome MCP Servers by wong2](https://github.com/wong2/awesome-mcp-servers)** (**[网站](https://mcpservers.org)**) - 由**[wong2](https://github.com/wong2)**整理的MCP服务器精选列表
- **[Discord服务器](https://glama.ai/mcp/discord)** – 由**[Frank Fiegel](https://github.com/punkpeye)**提供的专注于MCP的社区Discord服务器
- **[Discord服务器 (ModelContextProtocol)](https://discord.gg/jHEGxQu2a5)** – 在一个活跃的Discord社区中与开发者联系、分享见解并协作项目，致力于模型上下文协议，由**[Alex Andru](https://github.com/QuantGeekDev)**提供

- **[MCP徽章](https://github.com/mcpx-dev/mcp-badges)** – 通过清晰、引人注目的徽章快速突出您的MCP项目，由**[Ironben](https://github.com/nanbingxyz)**提供
- **[MCP服务器中心](https://github.com/apappascs/mcp-servers-hub)** (**[网站](https://mcp-servers-hub-website.pages.dev/)**) - 由**[apappascs](https://github.com/apappascs)**整理的MCP服务器精选列表
- **[MCP X社区](https://x.com/i/communities/1861891349609603310)** – 由**[Xiaoyi](https://x.com/chxy)**提供的MCP X社区
- **[mcp-cli](https://github.com/wong2/mcp-cli)** - 模型上下文协议的CLI检查器，由**[wong2](https://github.com/wong2)**提供
- **[mcp-get](https://mcp-get.com)** - 用于安装和管理MCP服务器的命令行工具，由**[Michael Latman](https://github.com/michaellatman)**提供
- **[mcp-guardian](https://github.com/eqtylab/mcp-guardian)** - 用于代理/管理MCP服务器控制的GUI应用程序+工具，由**[EQTY Lab](https://eqtylab.io)**提供
- **[mcp-manager](https://github.com/zueai/mcp-manager)** - 用于Claude Desktop安装和管理MCP服务器的简单Web UI，由**[Zue](https://github.com/zueai)**提供
- **[MCPHub](https://github.com/Jeamee/MCPHub-Desktop)** – 一个用于发现、安装和管理MCP服务器的开源MacOS和Windows GUI桌面应用程序，由**[Jeamee](https://github.com/jeamee)**提供
- **[mcp.run](https://mcp.run)** - 一个托管注册表和控制平面，用于安装和运行安全且可移植的MCP服务器。
- **[mcp-dockmaster](https://mcp-dockmaster.com)** - 一个开源UI，用于在Windows、Linux和MacOS上安装和管理MCP服务器。
- <img height="12" width="12" src="https://mkinf.io/favicon-lilac.png" alt="mkinf Logo" /> **[mkinf](https://mkinf.io)** - 一个开源托管MCP服务器注册表，加速AI代理工作流程。
- **[开源MCP服务器目录](https://github.com/chatmcp/mcp-directory)** - 由**[mcpso](https://mcp.so)**整理的MCP服务器精选列表
- <img height="12" width="12" src="https://opentools.com/favicon.ico" alt="OpenTools Logo" /> **[OpenTools](https://opentools.com)** - 一个用于查找、安装和构建MCP服务器的开放注册表，由**[opentoolsteam](https://github.com/opentoolsteam)**提供
- **[PulseMCP](https://www.pulsemcp.com)** ([API](https://www.pulsemcp.com/api)) - 社区中心和每周通讯，用于发现MCP服务器、客户端、文章和新闻，由**[Tadas Antanavicius](https://github.com/tadasant)**、**[Mike Coughlin](https://github.com/macoughl)**和**[Ravina Patel](https://github.com/ravinahp)**提供
- **[r/mcp](https://www.reddit.com/r/mcp)** – 由**[Frank Fiegel](https://github.com/punkpeye)**提供的专注于MCP的Reddit社区
- **[r/modelcontextprotocol](https://www.reddit.com/r/modelcontextprotocol)** – 模型上下文协议社区Reddit页面 - 讨论想法、解答疑问、与志同道合的人建立联系并展示您的项目！由**[Alex Andru](https://github.com/QuantGeekDev)**提供


- **[Smithery](https://smithery.ai/)** - 一个MCP服务器注册表，帮助为您的LLM代理找到合适的工具，由**[Henry Mao](https://github.com/calclavia)**提供
- **[Toolbase](https://gettoolbase.ai)** - 一个只需几次点击即可管理工具和MCP服务器的桌面应用程序，无需编码，由**[gching](https://github.com/gching)**提供

## 🚀 入门

### 在此存储库中使用MCP服务器
此存储库中基于TypeScript的服务器可以直接使用`npx`。

例如，这将启动[Memory](src/memory)服务器：
```sh
npx -y @modelcontextprotocol/server-memory
```

此存储库中基于Python的服务器可以直接使用[`uvx`](https://docs.astral.sh/uv/concepts/tools/)或[`pip`](https://pypi.org/project/pip/)。推荐使用`uvx`以便于使用和设置。

例如，这将启动[Git](src/git)服务器：
```sh
# 使用uvx
uvx mcp-server-git

# 使用pip
pip install mcp-server-git
python -m mcp_server_git
```

按照[这些](https://docs.astral.sh/uv/getting-started/installation/)说明安装`uv` / `uvx`，按照[这些](https://pip.pypa.io/en/stable/installation/)说明安装`pip`。

### 使用MCP客户端
然而，单独运行服务器并不是很有用，应该将其配置到MCP客户端中。例如，以下是使用上述服务器的Claude Desktop配置：

```json
{
  "mcpServers": {
    "memory": {
      "command": "npx",
      "args": ["-y", "@modelcontextprotocol/server-memory"]
    }
  }
}
```

使用Claude Desktop作为MCP客户端的其他示例可能如下所示：

```json
{
  "mcpServers": {
    "filesystem": {
      "command": "npx",
      "args": ["-y", "@modelcontextprotocol/server-filesystem", "/path/to/allowed/files"]
    },
    "git": {
      "command": "uvx",
      "args": ["mcp-server-git", "--repository", "path/to/git/repo"]
    },
    "github": {
      "command": "npx",
      "args": ["-y", "@modelcontextprotocol/server-github"],
      "env": {
        "GITHUB_PERSONAL_ACCESS_TOKEN": "<YOUR_TOKEN>"
      }
    },
    "postgres": {
      "command": "npx",
      "args": ["-y", "@modelcontextprotocol/server-postgres", "postgresql://localhost/mydb"]
    }
  }
}
```

## 🛠️ 创建您自己的服务器

有兴趣创建您自己的MCP服务器吗？请访问[modelcontextprotocol.io](https://modelcontextprotocol.io/introduction)上的官方文档，获取有关实现MCP服务器的全面指南、最佳实践和技术细节。

## 🤝 贡献

请参阅[CONTRIBUTING.md](CONTRIBUTING.md)了解有关为此存储库贡献的信息。

## 🔒 安全

请参阅[SECURITY.md](SECURITY.md)了解报告安全漏洞的信息。

## 📜 许可

该项目根据MIT许可证授权 - 详情请见[LICENSE](LICENSE)文件。

## 💬 社区

- [GitHub讨论](https://github.com/orgs/modelcontextprotocol/discussions)

## ⭐ 支持

如果您发现MCP服务器很有用，请考虑为存储库加星并贡献新的服务器或改进！

---

由Anthropic管理，但与社区共同构建。模型上下文协议是开源的，我们鼓励每个人贡献自己的服务器和改进！
