# Disaster-Recovery-Setup-for-Azure-Virtual-Machines
# 🌩️ Disaster Recovery Setup for Azure Virtual Machines (Azure VM)

## 📝 Objective
To implement a disaster recovery solution for Azure Virtual Machines using a **Recovery Services Vault** via the Azure Portal.

---

## ✅ Steps Performed

### 1. Created Azure Virtual Machine
- Navigated to Azure Portal → Virtual Machines → + Create
- Filled in basic configuration and disk settings
- Successfully deployed the VM

### 2. Created Recovery Services Vault
- Searched for **Recovery Services Vaults**
- Clicked on **+ Create** and entered the required details
- After deployment, went to the resource

### 3. Enabled Site Recovery
- From the vault, clicked **+ Enable Site Recovery**
- Selected the source region and subscription
- Selected the target virtual machine
- Configured replication settings (storage, cache, OS disk, etc.)
- Reviewed and enabled replication

### 4. Verified Replication
- Confirmed successful VM replication in the Site Recovery overview
- Disaster Recovery setup was completed successfully ✅

---

## 🔧 Tools Used
- Microsoft Azure Portal  
- No external tools or scripts required

---

## 🎯 Outcome
This configuration ensures **business continuity and VM availability** in case of outages or disasters by replicating workloads across regions.

---

## 📌 Skills Gained
- VM provisioning  
- Disaster Recovery planning  
- Azure Site Recovery configuration  
- Hands-on cloud infrastructure management

---

## 🔗 Tags
`#Azure` `#DisasterRecovery` `#VMReplication` `#CloudComputing` `#AzureSiteRecovery` `#GitHubProjects`
