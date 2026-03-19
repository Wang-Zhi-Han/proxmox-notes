# 🖥️ Proxmox LXC Learning Notes

## 📌 Project Overview
This repository documents my setup using Proxmox VE with LXC containers instead of traditional VMs.

---

## 🧠 為什麼選擇 LXC（Why LXC instead of VM）

Originally, I planned to use VMs, but:

- VM 無法有效共享 GPU
- GPU passthrough 設定複雜
- 資源利用率較低

👉 因此改用 LXC：

- 可以共享 GPU
- 輕量化
- 適合 AI / Docker / Jupyter

---

## ⚙️ 使用架構（Architecture）

- LXC1~3：實驗室同學使用

---

## 🔧 技術內容

- Proxmox VE
- LXC Container
- GPU Sharing (NVIDIA)
