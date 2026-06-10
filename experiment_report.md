# Experiment Report: Data Quality Impact on AI Agent

**Student ID:** AI20K-2A202600858
**Name:** Võ Huyền Khánh Mây
**Date:** 10-06-2026

---

## 1. Ket qua thi nghiem

Chay `agent_simulation.py` voi 2 bo du lieu va ghi lai ket qua:

| Scenario | Agent Response | Accuracy (1-10) | Notes |
|----------|----------------|-----------------|-------|
| Clean Data (`processed_data.csv`) | 10| | |
| Garbage Data (`garbage_data.csv`) | 0 | | |

---

## 2. Phan tich & nhan xet

### Tai sao Agent tra loi sai khi dung Garbage Data?

Agent tra loi sai khi dung Garbage Data vi du lieu nay co chat luong thap, bi nhiem khuan, sai lech, va thieu thong tin can thiet. Khi du lieu sai tu dau, Agent co the tiep nhan nhung thong tin sai lam hoac khong lien quan, dan den nhung cau tra loi khong chinh xac. Ngoai ra, khi du lieu thieu thong tin tuyen bo, Agent co the gap kho khan trong viec hieu va xu ly cac yeu cau, dan den nhung cau tra loi khong day du va thieu chinh xac.

---

## 3. Ket luan

**Quality Data > Quality Prompt?** 

Toi dong y voi quan diem nay. Qua trinh thuc hien thi nghiem cho thay rang chat luong du lieu co anh huong lon den ket qua cua AI Agent. Du lieu bi nhiem khuan, sai lech, hoac thieu thong tin co the dan den nhung cau tra loi sai lam, khong chinh xac, va thieu tin tuyen bo. Do do, viec dam bao chat luong du lieu la rat quan trong de AI Agent co the hoat dong hieu qua va dua ra nhung ket qua chinh xac.
