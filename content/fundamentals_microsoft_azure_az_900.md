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

*📅 Course: Microsoft Azure Fundamentals (AZ-900)*

