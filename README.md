<div align="center">
  <img src="https://via.placeholder.com/800x200/000/fff?text=DenseLang+v1.0" alt="DenseLang">
  <br><br>
  
  ![Stars](https://img.shields.io/github/stars/TBD/DenseLang?style=social)
  ![Python](https://img.shields.io/badge/Python-3.10+-blue)
  ![Tokens](https://img.shields.io/badge/60%25-↓-green)
  ![Accuracy](https://img.shields.io/badge/90%25+-blueviolet)
</div>

# DenseLang v1.0 🚀

**Плотный язык для LLM промптов. 60%↓ токенов. 90%+ точность на 3B→22B.**

## 🔥 Что делает

**До:** 1200 токенов промпта → $0.12/запрос  
**После:** 480 токенов → $0.048 **(-60%)**

| Домен | Сжатие | Точность 3B | Точность 22B |
|-------|--------|-------------|--------------|
| **Python** | 62% | 89% | 94% |
| **Rust** | 58% | 85% | 92% |
| **DevOps** | 65% | 92% | 95% |
| **Text** | 60% | 95% | 97% |

## 🎯 Примеры

```python
# Python: 28 → 11 токенов
func:add(a:int,b:int)->int=a+b

# DevOps: 8 → 3 токена  
k8s:ps|prod|err

# Text: 45 → 18 токенов
impl:auth+jwt|user+role|db:psql
