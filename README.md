

## 🌐 How to Set Up Microsoft Defender for Cloud on Azure

### 🧰 Prerequisites
- An active [Azure subscription](https://azure.microsoft.com/en-us/free/).
- Sufficient permissions (at least **Security Admin**, **Contributor**, or **Owner** on the subscription).

---

### ✅ Step 1: Sign in to Azure Portal
1. Go to [https://portal.azure.com](https://portal.azure.com).
2. Log in using your Azure account credentials.


---

### 🏠 Step 2: Navigate to Microsoft Defender for Cloud
1. In the left-hand menu, select **“Microsoft Defender for Cloud.”**
   - If not visible, use the search bar at the top and type "Defender for Cloud".
2. You will land on the **Overview** dashboard.

---

### 🔒 Step 3: Enable Defender for Cloud on Your Subscription
1. In the Defender for Cloud Overview page, click **"Environment settings"** in the sidebar.
2. Select the **subscription** you want to enable Defender for.
3. In the **"Defender plans"** tab, you’ll see a list of available protection plans.
4. Click **"Enable all"** or toggle the specific plans you want (e.g., Servers, Storage, SQL, Kubernetes, etc.).
5. Click **"Save"** to apply the changes.

> ⚠️ You may be prompted to upgrade from the free tier to the standard tier for advanced features.

---

### 💸 Step 4: Review Pricing Tier
- The **Free Tier** offers continuous security assessment and security recommendations.
- The **Standard Tier** (paid) adds threat protection and security alerts.
- You can select tiers per resource type (e.g., Standard for VMs, Free for SQL).

---

### 🛠️ Step 5: Configure Auto-Provisioning (Optional but Recommended)
1. Under **Environment settings**, select your subscription.
2. Click on the **"Auto provisioning"** tab.
3. Turn on auto-provisioning for agents like:
   - **Log Analytics Agent** for VM insights.
   - **Defender agent** for servers and Kubernetes.
4. Click **"Save"**.

---

### 🧪 Step 6: Explore Defender Recommendations
1. Go back to **Defender for Cloud > Recommendations**.
2. Review suggestions under **"Secure Score"** to improve your security posture.
3. Implement recommendations directly from the dashboard.

---

### 🛡️ Step 7: Simulate Threat Detection (Optional for Demo)
- Deploy a vulnerable VM or use Microsoft’s sample threats to generate alerts.
- Observe them in **Defender for Cloud > Security Alerts**.

---

### 📁 Step 8: Document in GitHub
Include the following in your GitHub project:
- Screenshots of each step.
- Links to Azure docs for deeper dives.
- Markdown badges for completion (optional).
- Security best practices.

---

Would you like a pre-formatted **README.md template** for this guide to use directly in your GitHub project
