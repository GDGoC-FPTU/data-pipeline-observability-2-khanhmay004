[![Open in Visual Studio Code](https://classroom.github.com/assets/open-in-vscode-2e0aaae1b6195c2367325f4f02e2d04e9abb55f0b24a779b69b11b9e10269abc.svg)](https://classroom.github.com/online_ide?assignment_repo_id=24112827&assignment_repo_type=AssignmentRepo)
# Day 10 Lab: Data Pipeline & Data Observability

**Student Email:** maykhanh004@gmail.com
**Name:** Võ Huyền Khánh Mây - 2A202600858

---

## Mo ta

Thử xây dựng một ETL pipeline đơn giản xử lý so sánh dữ liệu sạch và dữ liệu rác, so sánh chất lượng của dữ liệu ảnh hưởng tới kết quả của một AI Agent như thế nào.

---

## Cach chay (How to Run)

### Prerequisites
```bash
pip install pandas
```

### Chay ETL Pipeline
```bash
python solution.py
```

### Chay Agent Simulation (Stress Test)
```bash
# Mo ta cach ban chay thi nghiem Clean vs Garbage data
```

---

## Cau truc thu muc

```
├── solution.py              # ETL Pipeline script
├── processed_data.csv       # Output cua pipeline
├── experiment_report.md     # Bao cao thi nghiem
└── README.md                # File nay
```

---

## Ket qua

processed_data.csv chứa dữ liệu được xử lý
garbage_data.csv chứa dữ liệu rác
experiment_report.md chứa báo cáo kết quả thí nghiệm và phân tích
--> nói chung ai agent/hệ thống tốt thế nào mà data không được xử lý tốt thì cũng bỏ.