# Template-Engine

This project is a minimal template engine written in Python, inspired by Ned Batchelder's chapter from the *"500 Lines or Less"* book series.

## Features

- Pure Python template parsing and compilation
- Familiar syntax:
  - `{{ variable }}`
  - `{{ variable|filter }}`
  - `{% if condition %}`, `{% for item in list %}`, `{% endfor %}`
- Dot access and filters (e.g., `product.price|format_price`)
- No external dependencies
- Simple template reuse via Python

## 🛠️ Installation

No external packages are required. Just clone the repository:

```bash
git clone https://github.com/yourusername/template-engine.git
cd template-engine
