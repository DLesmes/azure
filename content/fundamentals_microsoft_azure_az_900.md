# 📘 Microsoft Azure Fundamentals (AZ-900) Course

> [Course content repository](https://github.com/platzi/AZ-900) - All course notes and materials in this repo

---

## 🎓 Class 2: Cloud Comparison - Private, Public & Hybrid

### ☁️ What is the Cloud and How Many Types Exist?

Cloud computing has become an indispensable tool in today's technological world. Understanding its capabilities and how its services are classified is essential to get the most out of it. Within the cloud concept, there are three major segments: **private cloud**, **public cloud**, and **hybrid cloud**. Each of these types offers different benefits and challenges that can influence the right solution for businesses or individuals.

---

### 🔒 What is Private Cloud?

The private cloud represents an environment where the infrastructure is exclusive to a single organization. Contrary to popular belief, it is not limited to just having physical servers in an office. A clear example is the ability to use a public cloud provider, like Azure, to create a private cloud. This allows, for example, creating a **VNet** that directly connects local devices with remote servers, ensuring privacy and exclusivity in communication.

#### ✅ Advantages of Private Cloud:

| Benefit | Description |
|---------|-------------|
| 🎛️ **Total Control** | Complete control over the infrastructure |
| 🛡️ **Enhanced Security** | Thanks to local storage and dedicated resources |
| 📋 **Regulatory Compliance** | Data remains within the company's network, meeting internal regulations |

---

### 🌐 What is Public Cloud?

The public cloud is offered by third parties, such as **Microsoft Azure**, **Amazon Web Services (AWS)**, and **Google Cloud**. These providers allow organizations to use shared resources maintained in massive data centers around the world.

#### ✅ Main Advantages of Public Cloud:

| Benefit | Description |
|---------|-------------|
| 📈 **Scalability** | Services can be increased or decreased according to demand |
| 💰 **Reduced Costs** | No need to maintain your own infrastructure, pay only for services used |
| 🌍 **Accessibility** | Services can be accessed from anywhere in the world |

#### ⚠️ Security Considerations:

> **Warning:** Organizations must consider security aspects. A configuration error can result in significant data breaches.

---

### 🔀 What is Hybrid Cloud?

The hybrid cloud is a combination of private and public clouds. It allows companies to maintain local controls while leveraging the scalability and additional services of the public cloud. A prominent example is the ability to host a local database and connect a web application in Azure that accesses that database.

#### ✅ Advantages of Hybrid Cloud:

| Benefit | Description |
|---------|-------------|
| 🔄 **Flexibility** | Combines the control of private cloud with the scalability of public |
| 📜 **Regulatory Compliance** | Allows keeping certain data locally, essential for governments requiring information to reside in their territory |
| ⚡ **Resource Optimization** | Efficient use of local environment and public cloud |

---

### 🤔 Which is the Best Option for You?

The choice between a private, public, or hybrid cloud depends on various factors such as:

- 🔐 **Security needs**
- 💵 **Budgets**
- ⚖️ **Legal requirements**

| Cloud Type | Best For |
|------------|----------|
| 🔒 **Private** | Total control and maximum security |
| 🌐 **Public** | Cost efficiency and scalability |
| 🔀 **Hybrid** | Balance between both worlds |

---

### 💡 Key Takeaways

> 🚀 Stay up to date with innovations and trends, as the world of cloud computing continues to evolve at an accelerated pace. Exploring and experimenting with these technologies will help you find the most suitable cloud solution for you or your organization.

---

### 📝 Class 2 Summary

```
┌─────────────────────────────────────────────────────────┐
│                    CLOUD TYPES                          │
├─────────────────────────────────────────────────────────┤
│  🔒 PRIVATE    │  Single org, full control, secure     │
│  🌐 PUBLIC     │  Shared resources, scalable, low cost │
│  🔀 HYBRID     │  Best of both worlds, flexible        │
└─────────────────────────────────────────────────────────┘
```

---

## 🎓 Class 3: Costs and Benefits of Azure Cloud Solutions

### 💭 How Can a Cloud Solution Help You and When Can It Hurt You?

Starting with a cloud service can be exciting. The possibilities seem limitless: virtual machines with hundreds of gigs of RAM and terabytes of storage, powerful GPUs... It seems like a technological dream come true. However, these services come with a cost, and the cloud can easily become a financial burden if not managed properly.

---

### 🎯 Why is it Important to Evaluate Your Cloud Needs?

It's fundamental to understand the relationship between the services you acquire and their costs. The cloud is designed to improve your operations, but if not managed wisely, costs can exceed benefits:

| ⚠️ Common Pitfall | Description |
|-------------------|-------------|
| 🔧 **Excessive Configurations** | Opting for hardware configurations too powerful for your current needs can be a costly mistake |
| 💡 **Common Mistakes** | Like forgetting to turn off virtual machines, which can inflate your monthly costs |

> 📊 A correct evaluation will allow you to mitigate cost risks associated with using unnecessary resources.

---

### 🧮 How to Use the Azure Pricing Calculator to Plan Your Costs?

Microsoft Azure offers an invaluable platform to forecast and plan your costs: the **[Azure Pricing Calculator](https://azure.microsoft.com/pricing/calculator/)**. This resource becomes an essential tool for any company that wants total control over their cloud budget:

#### 🔍 Navigation and Selection

In the pricing calculator, you can choose from a vast catalog of services. The most common fields include:

- 🖥️ Virtual Machines
- 🗄️ Databases
- 💾 Storage

#### ⚙️ Virtual Machine Specifications

Here you define key parameters such as:

| Parameter | Options |
|-----------|---------|
| 💻 **Operating System** | Windows, Linux, etc. |
| ⚡ **Compute Type** | High performance or general use |
| 🌍 **Region** | Where it will be deployed |

#### 💵 Cost Estimates

You can calculate typical monthly costs based on usage hours. For example:

| Configuration | Estimated Monthly Cost |
|---------------|----------------------|
| 🚀 High-performance VM | ~$7,000/month |
| 👨‍💻 Basic developer setup | ~$11/month |

---

### 🔬 What Benefits Does Exploring Example Scenarios Offer?

Exploring example scenarios in the Azure calculator allows you to forecast architectures and costs associated with configurations you might not have considered:

#### 📋 Key Benefits:

| Benefit | Description |
|---------|-------------|
| 📊 **Common Scenario Analysis** | By selecting example scenarios, you can see predefined configurations for web applications or CI/CD architecture |
| 💰 **Simulated Budget** | By adding these configurations to your budget, you get a clear view of associated costs |
| 📤 **Data Export** | Finally, you can export estimated costs to an Excel file for sharing or later analysis |

---

### 🏆 Key Takeaways

> 💡 Using the Azure Pricing Calculator will not only help you plan and forecast costs, but it will also ensure you're using cloud technology in favor of your operations, maximizing benefits and keeping your finances under control.

#### ✅ Action Items:

- 🧮 **Always estimate costs** before deploying resources
- ⏰ **Set up auto-shutdown** for development VMs
- 📊 **Review usage regularly** to avoid surprise bills
- 🎯 **Right-size your resources** - don't over-provision

---

### 📝 Class 3 Summary

```
┌─────────────────────────────────────────────────────────┐
│              AZURE COST MANAGEMENT                      │
├─────────────────────────────────────────────────────────┤
│  🧮 CALCULATOR    │  Plan & forecast your expenses     │
│  ⚠️ PITFALLS      │  Over-provisioning, forgotten VMs  │
│  📊 SCENARIOS     │  Use examples to estimate costs    │
│  💰 EXPORT        │  Share estimates via Excel         │
└─────────────────────────────────────────────────────────┘
```

---

## 🎓 Class 4: How to Create an Azure Account Securely

### 🔐 How to Create an Azure Account Securely?

Starting your Azure cloud journey can be exciting—and maybe a bit intimidating—especially when it comes to your account’s initial setup. Here’s a detailed, reliable guide to configure your Azure account securely and efficiently, while maximizing the benefits available to you.

---

### 🚀 What’s the First Step?

To begin, go to **[Azure Free Account / Free Services](https://azure.microsoft.com/es-es/free/)** and choose **“Try Azure for free”**. You’ll be asked to enter a valid email address, then follow a simple verification process.

For extra security, you may choose to receive a notification on your phone to confirm it’s really you signing in (a strong way to protect your account).

---

### 💳 What Should I Know About the Subscription?

When you create your account, Azure offers a **free subscription** with a **$200 USD credit**. This is typically enough to learn and experiment with the services used throughout the course.

You’ll also be asked to add a payment method (credit/debit card) to cover any usage that exceeds the free credit. In the context of this course, you shouldn’t need to spend beyond that credit if you follow the guidance and keep resources under control.

---

### 🛠️ Should I Add Technical Support?

During signup, Azure may offer you the option to add technical support. If you’re not planning to deploy high-impact or mission-critical solutions, it’s usually fine to skip paid support while you learn.

---

### 🌍 How Do I Configure My Account for Comfort?

After creating your account, Azure will show a quick tutorial. Spending a few minutes on it can help you understand the portal faster.

By default, Azure may appear in English, but you can change it easily:

- ⚙️ Go to **Settings**
- 🈯 Select **Language**
- 🇪🇸 Switch it to Spanish (or your preferred language)

---

### 🏁 Key Takeaways

> ✅ A secure setup from day one helps you learn confidently, reduces risk, and keeps your cloud experience smooth.

#### ✅ Action Items:

- 📱 Enable strong sign-in verification (phone prompt / MFA)
- 💳 Monitor your free credit so you don’t exceed it unintentionally
- 🧭 Take the portal tutorial to understand the basics faster
- 🌍 Set the portal language to what’s most comfortable for you

---

### 📝 Class 4 Summary

```
┌─────────────────────────────────────────────────────────┐
│            SECURE AZURE ACCOUNT SETUP                    │
├─────────────────────────────────────────────────────────┤
│  ✉️ SIGN UP       │  Use “Try Azure for free”           │
│  📱 VERIFY        │  Confirm sign-in for security        │
│  💳 CREDIT        │  $200 free credit (watch usage)      │
│  🌍 SETTINGS      │  Tutorial + language configuration   │
└─────────────────────────────────────────────────────────┘
```

---

## 🎓 Class 5: Installing Azure CLI (Windows, macOS, Ubuntu/Debian) + First Login

### 🧾 Summary: How to Install Azure CLI on Different Operating Systems?

Managing your Azure subscription has never been easier. This class walks you step by step through installing the **Azure Command-Line Interface (Azure CLI)** so you can manage Azure from a terminal. 💻

This is especially useful if you’re a contributor (not the main subscription admin), because you might not see everything in the Azure Portal depending on permissions and roles—but with CLI you can still work efficiently with what you do have access to. 🔍

#### 🔗 Official installation guide

- 📘 **Microsoft Learn**: [Install Azure CLI](https://learn.microsoft.com/es-es/cli/azure/install-azure-cli?view=azure-cli-latest)

---

### 🪟 How to Install Azure CLI on Windows

- ⬇️ **Download the installer** from the class resources / official guide
- ▶️ **Run the installer** and follow the usual flow: *Next → Next → Next*

✅ Quick and painless.

---

### 🍎 How to Install on macOS (Homebrew)

If you use macOS, **Homebrew** makes installation simple:

- 🧑‍💻 **Run a single command** in your terminal (as provided in the official guide)

---

### 🐧 How to Install on Ubuntu and Debian

Just like macOS, installation on Ubuntu/Debian is straightforward:

- 🧩 **Run the install command/script** from the official guide
- ⚙️ The script will download and configure Azure CLI automatically

---

### ✅ How to Verify the Installation Worked

No matter which OS you’re using, open a terminal and run:

```bash
az
```

If installation is correct, you’ll see a long list of available commands. At the top, you’ll typically see the **Azure name in ASCII art**, which is a great sign everything is working. 🎉

---

### 🔐 How to Sign In to Azure from Azure CLI

After confirming the CLI works, sign in:

```bash
az login
```

This usually opens a browser to authenticate. If it doesn’t (or your environment is restricted), use device code login:

```bash
az login --use-device-code
```

Then:

- 🔢 **Copy the code** shown in your terminal
- 🌐 **Paste it into the webpage** that opens to complete authentication

---

### 🧭 Verify Subscriptions + Confirm Your Active Context

Once logged in, Azure CLI will list your accessible subscriptions. Choose the one you want to use, then verify your current selection:

```bash
az account show
```

✅ This confirms which subscription/account context you’re using—so you can confidently deploy resources from the portal or straight from the CLI. 🚀

---

### 📝 Class 5 Summary

```
┌─────────────────────────────────────────────────────────┐
│                    AZURE CLI BASICS                      │
├─────────────────────────────────────────────────────────┤
│  ⬇️ INSTALL       │  Windows / macOS / Ubuntu-Debian     │
│  ✅ VERIFY        │  Run `az` to confirm it works         │
│  🔐 LOGIN         │  `az login` / `--use-device-code`     │
│  🧾 CONTEXT       │  Check active subscription/account    │
└─────────────────────────────────────────────────────────┘
```

---

## 🎓 Class 6: Monitoring and Managing Your Costs in Azure

### 🧾 Summary: How to Monitor and Manage Your Costs in Azure?

Cost management in Azure is a key skill for any IT professional. Estimating costs and keeping cloud resources under control helps you use your budget efficiently **and** maintain optimal system performance. While the Azure Pricing Calculator is a great starting point, real usage can differ—so learning where to monitor actual spend in the Azure Portal is essential. 💸📊

---

### 🔑 How to Access the Subscriptions Section in Azure

Go to the **Azure Portal** and open **Subscriptions**:

- 🔎 If you don’t see it right away, use the search bar and type **“Subscriptions”**
- 🗝️ You’ll land on the subscriptions page where you can view your available subscriptions and drill into details

---

### 📈 What Cost Information Can You See?

Inside the subscription view, Azure surfaces cost-related insights that help you stay on top of spending:

#### 📊 Cost charts

- 📉 You’ll see charts showing your **used amount** and **remaining amount** (when applicable)
- 🔮 Azure can also **project end-of-month costs** based on your current resource usage (a forward-looking estimate to prevent surprises)

#### 🧾 Resource breakdown

As you scroll down, you can identify:

- 🧱 Which resources are costing the most
- 🎯 Where you should investigate sizing, schedules, or cleanup

---

### ⚙️ How to Optimize Resource Management

Monitoring cost per resource is the best way to avoid unnecessary spend. When you see a resource driving high costs, check whether it’s over-sized compared to what you actually need.

Helpful ways to organize your review:

- 📍 **By location/region**
- 🏷️ **By resource name**
- 🗂️ **By resource group**

---

### 🛡️ What If You Find Unsecured Resources?

Any resource flagged as **not secure** should be reviewed and secured as a priority. 🚨  
Unsecured resources can introduce **security risk** and also **cost risk** (for example, unexpected usage due to exposure or misconfiguration).

---

### 💡 Does Azure Provide Personalized Recommendations?

Yes—Azure can provide recommendations based on how you’re using resources. For example:

- ⬆️ Suggesting a move from a **basic** plan to a **premium** plan if usage patterns justify it
- 🧠 Highlighting optimization opportunities to improve cost-efficiency

Following these recommendations (with good judgment) can help optimize both performance and cost. ✅

---

### 🧮 How to Set Budgets in Azure

In **Cost Management**, you’ll find **Budgets**—a feature that lets you set spending limits and receive notifications if you approach or exceed them. 🔔

Example:

- 🖥️ If you decide a VM shouldn’t exceed **$100/month**, you can create a budget and have Azure alert you as you near that threshold.

---

### 🏁 Key Takeaways

- 📊 Use **Subscriptions + Cost Management** to track real spend (not just estimates)
- 🧹 Periodically review for unused resources and delete what you don’t need
- 🎯 Right-size and organize resources to keep spending predictable
- 🔔 Set budgets early to avoid surprise bills

---

### 📝 Class 6 Summary

```
┌─────────────────────────────────────────────────────────┐
│                AZURE COST MONITORING                     │
├─────────────────────────────────────────────────────────┤
│  🔎 SUBSCRIPTIONS  │  Find costs + projections            │
│  🧾 BREAKDOWN      │  Identify top-cost resources          │
│  ⚙️ OPTIMIZE       │  Right-size + organize by groups      │
│  🔔 BUDGETS        │  Alerts when you approach limits      │
└─────────────────────────────────────────────────────────┘
```

---

## 🎓 Class 7: Navigating the Azure Portal

### 🧾 Summary: How Do You Navigate the Azure Portal?

The Azure Portal is a powerful tool for managing and deploying cloud resources. With **nearly 200 services** available, it can feel overwhelming at first—and that’s completely normal. 😅  
In this class, you’ll learn how to navigate the portal and align Azure resources with your specific needs. 🧭

---

### 🧱 What Is the Azure Main Menu?

When you sign in to the Azure Portal, you’ll notice a **top (horizontal) menu** that helps you quickly access things you’ve used recently.

- 🕘 **Recent items**: jump back into the last services/resources you worked on
- ➕ **Create a resource**: a quick entry point to deploy new services fast
- 🎛️ **Personalization**: the portal adapts based on your usage, and you can customize what you pin and how you navigate

---

### 🔍 How Do You Explore Service Options?

Azure has many categories of ready-to-deploy services. In the portal, you can explore categories and also discover services you might not have used before.

Make sure to explore:

- 📚 **All services**: a complete list of resources organized by category (super helpful when you don’t know the exact name)

#### ⭐ Popular categories to know

- 🤖 **AI + Machine Learning**: Azure AI Foundry, Machine Learning
- 🗄️ **Databases**: Azure Cosmos DB, Azure SQL (e.g., Hyperscale)
- 📦 **Containers**: Container Instances, Container Registry

---

### 🎯 What Does “Specialization” Mean in Azure?

Azure is huge. It’s practically impossible to master every service—and that’s expected. ✅  
Instead, most professionals specialize in a domain, for example:

- 🗃️ **Data**
- 🧩 **Distributed applications**
- 🖥️ **Compute / infrastructure**

Specializing lets you go deep where it matters, without needing to know every single Azure product. 🧠

---

### 🔄 How Do You Stay Up to Date in Azure?

Azure changes constantly: new services appear, others evolve, and features get renamed or reorganized. Keeping up with everything is hard, so use a strategy:

- 🧭 Pick a category you care about
- 🧪 Deploy and experiment with services in that category
- 🧹 Delete resources when you’re done learning (to avoid cost surprises)

> 🧠 Experimentation is your best friend: deploy → learn → clean up.

---

### 🚀 Start Exploring!

With this, you’re ready to dive into Azure. Don’t worry if it feels like a lot in the beginning—practice will quickly make the portal feel familiar. 💪  
Explore, test, and iterate so you can choose the best tools for your projects. 🌩️

---

### 📝 Class 7 Summary

```
┌─────────────────────────────────────────────────────────┐
│                AZURE PORTAL NAVIGATION                   │
├─────────────────────────────────────────────────────────┤
│  🧱 MAIN MENU      │  Recent items + Create resource      │
│  📚 ALL SERVICES   │  Browse services by category         │
│  🎯 SPECIALIZE     │  Go deep in a domain                 │
│  🧪 EXPERIMENT     │  Deploy → learn → delete             │
└─────────────────────────────────────────────────────────┘
```

---

## 🎓 Class 8: What’s Hidden in the Azure Portal “Containers” Category?

### 🧾 Summary: What Does the Azure Portal Hide in the Containers Category?

Exploring Azure can be exciting! 🎉 But here’s a key tip: sometimes there are **more services available than what the portal shows at first glance**. For example, when you open the **Containers** area in the Azure Portal, it may look like there are only a couple of options—but the broader Azure catalog reveals many more container-related services. 👀📦

#### 🔗 Azure Products catalog (official)

- 🧩 **Azure Products**: [Browse all Azure products](https://azure.microsoft.com/es-es/products)

---

### 📦 Where Can You Find All Available Container Services?

On the Azure Products site, services are organized similarly to the portal. When you select the **Containers** category, you’ll see **many more options** than what’s immediately visible in the portal UI.

Also note: some services can appear under multiple categories. For example, **Azure Kubernetes Service (AKS)** may show up in more than one place depending on how Microsoft groups services. That’s normal—and the catalog helps you find the “full list” faster. 🗂️✅

---

### 🚀 How to Get Started with Azure Container Apps

**Azure Container Apps** is a powerful and popular option in Azure. Once you select it from the catalog, you’ll typically find a richer set of resources such as:

- 🆚 Container comparisons
- ⚡ Quickstarts / getting-started guides
- 📘 Documentation links

This helps you learn faster and get the most out of both the portal and the online docs. 🧠

---

### 📚 Why Microsoft Learn Documentation Matters

Here’s a cool Azure reality: sometimes **documentation is available even before a product reaches general availability (GA)**. That often happens with services in **preview**—you can still access lots of learning material and references early. 🧪📄

Microsoft invests heavily in detailed documentation on **Microsoft Learn**, so you can explore deeply and be ready to implement new tools when they’re fully released. ✅

---

### 🧰 How Can Azure Documentation Help You?

Good docs don’t just describe products—they teach you how to use them:

- 🔮 Prepares you for upcoming releases
- 🏗️ Offers strategies and patterns for implementation
- 🧭 Gives you a reliable reference even while features evolve

---

### 💡 Recommendations to Get the Most Out of Azure

- 🧩 **Explore the full catalog** using the Azure Products link
- 📚 **Strengthen your knowledge with Microsoft Learn docs**
- 🎯 **Specialize in a favorite tool** (like Azure Container Apps) and go deep
- 🔄 **Stay current** by continuing your learning and experimenting

> 🚀 Azure has an impressive ecosystem of tools and documentation—keep exploring and you’ll always be one step ahead.

---

### 📝 Class 8 Summary

```
┌─────────────────────────────────────────────────────────┐
│                CONTAINERS IN AZURE                        │
├─────────────────────────────────────────────────────────┤
│  👀 HIDDEN OPTIONS  │  Portal shows some, catalog shows all │
│  🧩 PRODUCTS PAGE   │  Browse container services by category │
│  🚀 CONTAINER APPS  │  Quickstarts + comparisons + guides   │
│  📚 DOCS EARLY       │  Learn even during preview phases     │
└─────────────────────────────────────────────────────────┘
```

---

## 🎓 Class 9: Improve Resource Management in Azure with Tags

### 🧾 Summary: How Can I Improve Resource Management in Azure with Tags?

In cloud environments—especially on platforms like Azure—keeping resources well-organized is critical. One simple (and often underrated) superpower is **tags**. 🏷️  
Tags help you categorize, search, govern, and manage resources at scale, making your Azure environment easier to understand and operate. 📌

---

### 🏷️ What Are Azure Tags and How Do You Create Them?

**Tags are metadata applied to Azure resources.** They are **key-value pairs** that help identify resources based on your own classification.

When you create a resource (for example, a **Resource Group**), you typically define:

- 🏷️ **Name**
- 🌍 **Region/location** (ideally close to the people/apps that will use it)

Then you can add **tags** as extra context.

Example:

- 📦 Resource group name: `my-first-rg`
- 🔑 Tag key: `environment`
- 🧪 Tag value: `testing`

This makes it instantly clear that the resources inside are meant for experiments or learning. ✅

> 💡 In the Azure Portal, tags often show in the resource overview. If you don’t see them immediately, it can sometimes be a UI/zoom/layout issue—scrolling or adjusting zoom may reveal the section.

---

### ⭐ Why Are Tags Important in Azure?

Tags help you:

- 🎯 **Understand purpose fast**: know what a resource is for without guessing
- 🧪 **Spot “temporary” resources**: identify volatile/learning resources (e.g., `testing`, `dev`)
- 🔎 **Search and filter efficiently**: quickly find and manage resources across your subscription(s)

---

### 🏢 What’s the Business Value of Tags?

Tags are extremely flexible—each organization can adapt them to its needs. Common enterprise patterns include:

- 🧪 **Environment**: `dev`, `test`, `prod`
- 👤 **Owner / team**: who is responsible for the resource
- 🧾 **Cost tracking**: `CostCenter`, `Client`, `Project`
- 🛡️ **Security classification**: `Confidential`, `Public`

Tags act like a compass in a large Azure estate—bringing clarity, governance, and better cost transparency. 🧭

---

### ⚠️ Important Notes (Microsoft Learn-style guidance)

- 🔑 **Tags are key-value pairs** used for identification and organization
- 📝 **Tags are stored as plain text** → **do not put secrets or sensitive data in tags**
- 🌐 **Be careful using non-English languages** in tags in some contexts (it can occasionally cause decoding/progress issues depending on tooling and integrations)
- 🔤 **Tag names are case-insensitive** for operations (treat `Owner` and `owner` as the same key)
- 🚫 **Tag names can’t contain certain characters**: `<`, `>`, `%`, `&`, `` ` ``, `?`, `/`

---

### 🎯 Best Uses of Tags in Azure

- 🏛️ **Organization & governance**: classify by environment, project, department
- 💸 **Cost control**: add `Owner` / `CostCenter` to track spend by team/client
- 🛡️ **Security & compliance**: classify sensitivity and enforce rules
- 🤖 **Automation & management**: filter/apply policies using **Azure Policy** or Automation based on tags

📌 Recommendation: define a clear convention (`key:value`), tag all important resources consistently, and avoid “tag spam” that no one maintains. ✅

---

### 📝 Class 9 Summary

```
┌─────────────────────────────────────────────────────────┐
│                    AZURE TAGS                            │
├─────────────────────────────────────────────────────────┤
│  🏷️ METADATA       │  Key-value pairs for resources       │
│  🔎 SEARCH          │  Filter & find resources fast        │
│  💸 COST            │  Track spend by owner/cost center    │
│  🛡️ GOVERNANCE      │  Enforce rules with policy/automation │
└─────────────────────────────────────────────────────────┘
```

---

## 🎓 Class 10: Create an Azure Storage Account + Automate Deployments with ARM Templates

### 🧾 Summary: How Do I Create a Storage Account in Azure?

To start using Azure services, you create resources based on your needs. One foundational resource is a **Storage Account**, which lets you store data in Microsoft’s cloud. ☁️💾

---

### 🏗️ Create a Storage Account (Portal)

1. 🌐 Open the **Azure Portal** and select **Create**
2. 🔎 Search for **Storage account** (using your portal language helps)
3. 🧾 Select **Storage account** → **Create**
4. ✅ Fill in the required fields:
   - 🗂️ **Resource group**: select the one you’ll use for the course/lab
   - 🏷️ **Storage account name**: must be **globally unique**
   - 🌍 **Region**: preferably the same region as your resource group (and close to users)
   - ⚙️ **Performance**: choose **Standard** for learning environments
   - 💸 **Redundancy**: choose **Locally-redundant storage (LRS)** for the lowest cost option
5. 🔍 Click **Review + create**
6. 🚀 After validation passes, click **Create** → then **Go to resource**

---

### 🧩 Azure Naming Rules (Why Your Storage Account Name Might Fail)

Azure validates the storage account name automatically. For storage accounts, the name is similar to a domain-style identifier:

- ✅ Must be **unique**
- 🚫 No uppercase letters
- 🚫 Avoid special punctuation (Azure will reject invalid characters)

📌 For learning: stick to the cheapest defaults (Standard + LRS). Premium options can generate unnecessary costs. 💰

---

### 🤖 What Are ARM Templates (and Why Automate)?

After creating a resource, you can export its configuration as an **ARM template (Azure Resource Manager template)** to automate future deployments. This is extremely useful when you need to recreate similar resources repeatedly with small changes (like the name). 🔁

#### ✅ Why automation matters

- ⏱️ **Time savings**: no repeated clicking through forms
- 🧱 **Consistency**: same configuration every time
- 📈 **Scalability**: deploy many similar resources easily
- 🧾 **Version control**: templates can live in Git
- 🔄 **CI/CD ready**: integrate infra deployments into pipelines

> 🧠 The portal is great for learning, but manual deployment doesn’t scale. Automation is how real environments are built.

---

### 📤 Export an ARM Template from an Existing Resource

1. 📦 Open your **Storage account** resource
2. 🧭 In the left menu, go to **Automation** (or **Automation** section)
3. 📄 Select **Export template**
4. ⬇️ Download the ZIP (often named something like `ExportedTemplate.zip`)
5. 🗜️ Extract it—you’ll typically find:
   - `template.json` (full resource definition)
   - `parameters.json` (values you can change per deployment)

#### 🧪 Simplified ARM template example (`template.json`)

```json
{
  "$schema": "https://schema.management.azure.com/schemas/2019-04-01/deploymentTemplate.json#",
  "contentVersion": "1.0.0.0",
  "parameters": {
    "storageAccountName": {
      "type": "string",
      "metadata": {
        "description": "Storage account name"
      }
    }
  },
  "resources": [
    {
      "type": "Microsoft.Storage/storageAccounts",
      "apiVersion": "2021-04-01",
      "name": "[parameters('storageAccountName')]",
      "location": "centralus",
      "sku": { "name": "Standard_LRS" },
      "kind": "StorageV2"
    }
  ]
}
```

---

### ♻️ Reuse an ARM Template for New Deployments (Portal)

1. 🔎 Search for **Template deployment**
2. 🧩 Open it and choose **Build your own template in the editor**
3. ⬆️ Click **Load file** and upload your `template.json`
4. 💾 Click **Save**
5. 🧾 Fill in parameters (like a new unique storage account name) and deploy

---

### 💻 Deploy an ARM Template Using Azure CLI

Supporting docs:

- 📘 [az deployment group](https://learn.microsoft.com/en-us/cli/azure/deployment/group?view=azure-cli-latest)

Commands:

```bash
az login
az account set --subscription "YOUR_SUBSCRIPTION_NAME"

az deployment group create \
  --resource-group YOUR_RESOURCE_GROUP_NAME \
  --template-file path/to/template.json \
  --parameters path/to/parameters.json
```

✅ This automates repeat deployments—typically you only change parameters like the storage account name.

---

### 📝 Class 10 Summary

```
┌─────────────────────────────────────────────────────────┐
│          STORAGE ACCOUNT + AUTOMATION (ARM)              │
├─────────────────────────────────────────────────────────┤
│  💾 STORAGE         │  Standard + LRS for low-cost labs    │
│  🏷️ NAMING          │  Unique name, no uppercase/specials  │
│  📤 EXPORT ARM       │  Automation → Export template        │
│  ♻️ REDEPLOY         │  Template deployment / Azure CLI      │
└─────────────────────────────────────────────────────────┘
```

---

## 🎓 Class 11: Why Automate Infrastructure in Azure? (Azure CLI Basics)

### 🧾 Summary: Why Do We Need to Automate Infrastructure in Azure?

Infrastructure automation isn’t just a trend—it’s a necessity in modern development environments. 🚀  
Think about scenarios like:

- 👩‍💻 Deploying infrastructure for **5 developers** before merging their work
- 👥 Scaling that process to **50 people**
- ⏰ Spinning up infrastructure **minutes before work starts** and shutting it down **at the end of the day**

When scale increases, manual work in the portal (and even template-heavy workflows) becomes painful. That’s where **Azure CLI (`az`)** becomes a powerful ally. 💻⚡

---

### 🛠️ How to Use Azure CLI to Create Resources

Azure CLI lets you create resources using simple commands.

#### 🗂️ Create a Resource Group

```bash
az group create -l eastus2 -n GrupoRecursosCLI
```

- 📍 `-l` / `--location`: Azure region (here: `eastus2`)
- 🏷️ `-n` / `--name`: resource group name

✅ This is the CLI equivalent of creating a resource group in the portal—done in seconds. The CLI returns a JSON payload describing the created resource.

#### 💾 Create a Storage Account

```bash
az storage account create -n cuentacliamin001 -g GrupoRecursosCLI -l eastus2 --sku Standard_LRS
```

- 🏷️ `-n` / `--name`: **globally unique** storage account name (tip: add numbers to avoid collisions)
- 🗂️ `-g` / `--resource-group`: where to deploy
- 📍 `-l` / `--location`: region
- 💸 `--sku Standard_LRS`: Standard performance + locally redundant storage (cost-friendly and great for labs)

---

### 🧭 How to Discover Available Commands and Parameters

When you’re starting out, the biggest question is usually “what flags do I need?” You have two main ways:

#### 🆘 Use built-in help

```bash
az --help
az storage --help
az storage account --help
```

This lets you “drill down” until you find the command and the required parameters. 🔎

#### 🌐 Use Microsoft Learn documentation

If you prefer a visual reference with examples, Microsoft Learn lists commands, required/optional parameters, and usage patterns.

Recommended resource:

- 📘 [Manage Azure resources using Azure CLI](https://learn.microsoft.com/es-es/azure/azure-resource-manager/management/manage-resources-cli)

---

### 🏁 Key Takeaways

- ⚡ Azure CLI reduces clicks and speeds up provisioning
- ✅ Automation improves consistency and reduces human error
- 📚 Built-in help + Microsoft Learn docs make discovery easy

---

### 📝 Class 11 Summary

```
┌─────────────────────────────────────────────────────────┐
│                 AZURE CLI AUTOMATION                     │
├─────────────────────────────────────────────────────────┤
│  🗂️ GROUP CREATE    │  `az group create`                  │
│  💾 STORAGE CREATE  │  `az storage account create`         │
│  🆘 HELP SYSTEM     │  `az ... --help`                     │
│  📘 DOCS            │  Learn examples + parameters         │
└─────────────────────────────────────────────────────────┘
```

---

*📅 Course: Microsoft Azure Fundamentals (AZ-900)*

