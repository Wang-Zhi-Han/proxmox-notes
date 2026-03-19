# 📦 Create LXC in Proxmox

## 📌 步驟

1. 下載 Template（Ubuntu / Debian）
2. 建立 LXC Container
3. 設定 CPU / RAM
4. 設定 Storage
5. 設定 Network

---

## ⚙️ GPU 使用（重要🔥）

LXC 可以直接使用 host GPU：

### 必要條件
- 安裝 NVIDIA Driver（在 host）
- 設定 /dev/nvidia*

### 優點
- 不需要 passthrough
- 多個 container 可共用 GPU

---

## 🧠 Notes

- 適合 AI / Docker / Jupyter
- 比 VM 更省資源
