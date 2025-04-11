# Joint-NER-Relation

Модель для совместного извлечения именованных сущностей (NER) и отношений между ними (RE) с использованием BERT и Graph Attention Networks.

Архитектура:
- BERT для контекстуальных эмбеддингов
- CRF для последовательностей NER-меток
- GAT (Graph Attention Network) для анализа отношений
