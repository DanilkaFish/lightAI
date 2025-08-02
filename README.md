# 🧠 Статьи и заметки

## 📚 Оглавление

- [AI](#-ai)
- [Light](#-light)
- [Light + AI](#-light--ai)

---

## 🧠 AI

- [x] **[CompactifAI: Extreme Compression of LLM via TN](ai/CompactifAI.md)** — Уменьшения числа параметров за счет СВД для LlaMA-2 2.1B ~~7b~~ сохранением точности. 2019 - MNIST, CIFAR [Compressing deep neural networks by matrix product operator](https://arxiv.org/pdf/1904.06194)
- [x] **[Tensor Product Attention Is All You Need](https://arxiv.org/pdf/2501.06425)** — замена слоя attention (вычислительно самого большого) в трансформаторе через MPO, меньше параметров, те же результаты.
- [ ] **[Deep Learning Is Singular, and That’s Good](https://www.suswei.com/publication/wei-2022-singular/wei-2022-singular.pdf)** — Регулярные модели -- положительно опредленная матрица Фишера, Нейронки сингулярны, можно ввести RLCT, связанную с числом эффективных Параметров d' (если w решение,то существует d-d' направлений, варьирование в которых которые не меняют решения). Показано, что лучше, чем MAP и MLE, работает baeys predictive rule. Есть книга по SLT 
- [ ] **[Prefix tuning](ai/PT.md)**

## 🔦 Light

## ⚡ Light + AI

- [x] **[Shedding Light on the Future: Exploring Quantum Neural Networks through Optics](light-ai/light_review.md)** -- просто совсем небольшой обзор.
- [x] **[Continuous-variable quantum neural networks](light-ai/QCNN.md)** — предложена CV PQC, для которой классический feed-forward слой является частным случаем при эмбединге через квадратуры.
- [x] **[Quantum kernel machine learning with continuous variables](light-ai/CV_QKML.md)** — рассматривается классификация на методе опорных векторов, голоморфный функции, аналитика для квантовых ядер 
- [x] **[Continuous-Variable Quantum Encoding Techniques](https://arxiv.org/pdf/2504.06497)** — индусы прогнали кодировку с помощью D и S в разных задачах машинного обучения

## Quantum + AI

- [x] **[Quantum-Enhanced LLM Efficient Fine Tuning](quantum-ai/QuantumPEFT.md)** — Добавление "внешнего" квантового слоя (Подобие resnet), что позволяет лучше улавливать нелинейные отношения, квантовые шумы способствуют стабильности. Эмбединг через углы.
- [x] **[The power of quantum neural networks](quantum-ai/QNNpower.md)** — Матрица Фишера для опредения числа эффективных параметров, плато, обобщающей способности. Чем выше ранг матрицы Фишера, тем лучше обобщающая способность(?), тренируемость. Кванты могут превосоходить классические DL.
- [x] **[Quantum-Based Compression for Parameter Efficiency](quantum-ai/ParameterEff.md)** — Генерация параметров для классических PEFT с помощью PQC. Лучшая точность при том же небольшом числе параметров. Много вычислительный инфы по эксперименту.
- [ ] **[Theory for Equivariant Quantum Neural Networks](quantum-ai/EQNN.md)**
- [ ] **[Supervised learning with quantum enhanced feature spaces](quantum-ai/QenhancedSpace.md)**
- [ ] **[Challenges and opportunities in quantum machine learning](https://arxiv.org/pdf/2303.09491)** — хороший обзор, много ссылок.
- [x] **[Gpt on a quantum computer](quantum-ai/QGPT.md)** — фреймворк для почти точного переноса классического блока трансформера из gpt полностью на квантовый компьютер. Эмбеддинг через амплитуды [CQSP](https://arxiv.org/pdf/2202.11302).
- [ ] **[Errors in VQC for regression problems](https://arxiv.org/pdf/2206.04804)**
- [ ] **[Quantum generalisation of feedforward neural networks](https://www.nature.com/articles/s41534-017-0032-4)** — NN есть частный случай QNN.

## 🗒 Формат заметок

Внутри каждого `.md` файла:  

- краткое описание
- ключевые идеи
- формулы
- код/схемы (если есть)
- мои замечания

Шаблон — [здесь](TEMPLATE.md)
