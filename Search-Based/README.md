## 基于搜索的问题求解
> 整理:[mindcont](https://github.com/mindcont) - 原著 《人工智能》 [日]沟口理一郎 石田 亨编

人工智能要解决的问题，大部分不具备明确的解题步骤。这类问题可以采用搜索方法解决，但是在解决过程中，会伴随着产生试行错误。

本章将对采用**状态空间图的问题**表示方法、采取纵向搜索和横向搜索的**系统的搜索方法**、运用**启发式**(已发现的知识)的搜索方法、表示问题分解的与(AND)/或(OR)图的搜索，以及在计算机国际象棋等方面用到的**博弈树搜索**，进行分析和说明。

####　[搜索与人工智能的关系](基于搜索的问题求解/搜索与人工智能的关系/README.md)

| 章节 | 内容 |
| -- | -- |
| [八数码魔方](Search-Based/The-Relationship/八数码魔方.md) | 1:2 |
| [状态空间表示](Search-Based/The-Relationship/状态空间表示.md) | 1:3 |
| [与图有关的术语](Search-Based/The-Relationship/与图有关的术语.md) | 1:4 |

####　[逐个搜索](基于搜索的问题求解/逐个搜索/README.md)

| 章节 | 内容 |
| -- | -- |
| [随机搜索](Search-Based/One-by-one-search/随机搜索.md) | 1:2 |
| [CLOSED表的引入](Search-Based/One-by-one-search/CLOSED表的引入.md) | 1:3 |
| [OPEN表的引入](Search-Based/One-by-one-search/OPEN表的引入.md) | 1:4 |
| [纵向搜索](Search-Based/One-by-one-search/纵向搜索.md) | 1:5 |
| [横向搜索](Search-Based/One-by-one-search/横向搜索.md)| 1:6 |
| [均一代价搜索](Search-Based/One-by-one-search/均一代价搜索.md) | 1:7 |

####　[应用智能的搜索](基于搜索的问题求解/应用智能的搜索/README.md)

| 章节 | 内容 |
| -- | -- |
|[启发式搜索](Search-Based/Intelligent-Search/启发式搜索.md) | 1:2 |
|[登山法和最佳优先搜索](Search-Based/Intelligent-Search/登山法和最佳优先搜索.md) | 1:3 |
| [A*算法](Search-Based/Intelligent-Search/A算法.md) | 1:4 |
| [约束的利用](Search-Based/Intelligent-Search/约束的利用.md)| 1:5 |

#### [对问题进行分割后进行搜索](基于搜索的问题求解/对问题进行分割后进行搜索/README.md)

| 章节 | 内容 |
| -- | -- |
|  [与/或(AND/OR)图表示](Search-Based/Split-and-Search/与或图表示.md) | 1:2 |
| [与/或(AND/OR)图搜索](Search-Based/Split-and-Search/与或图搜索.md) | 1:3 |

#### [博弈树的搜索](基于搜索的问题求解/博弈树的搜索/README.md)