# 📘 Microsoft Azure Fundamentals (AZ-900) Course

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

*📅 Course: Microsoft Azure Fundamentals (AZ-900)*

