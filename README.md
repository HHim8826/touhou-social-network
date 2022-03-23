Check out the [original project](https://github.com/King-of-Infinite-Space/genshin-social-network) for more information.\
**—> [HHim8826/touhou-social-network](https://hhim8826.github.io/touhou-social-network/) <—**

---
#### 布局说明 | About layouts

本项目使用[Cytoscape.js](https://js.cytoscape.org/)生成网络图。采用了以下布局。\
This project uses __ to generate network graph. The following layouts are used.

- [fcose](https://github.com/iVis-at-Bilkent/cytoscape.js-fcose)：基于力导向算法。（进行力学模拟，顶点互相排斥，边提供张力，直至平衡。）Based on force-directed layout. Nodes repel each other and edges pull them together. The forces are simulated until equilibrium is reached.

- [avsdf](https://github.com/iVis-at-Bilkent/cytoscape.js-avsdf)：在圆周上排列顶点，使得边的交叉尽可能少。The nodes are distributed along a circle such that the crossing of edges is minimized.

- custom：同心圆布局。初始状态下边越多的顶点越靠近中心。选中人物后以其为中心，与之连接越多的人物越靠近中心。A concentric layout. Initially, nodes with more edges are closer to the center. When a character is selected, it moves to the center and nodes with more edges with it are closer.

#### 探索此图 | Explore the graph

`cy` 变量是Cytoscape.js图的对象。`stats`变量包含了每个节点的统计数字。可在控制台进行探索。\
`cy` is the variable for Cytoscape.js graph object. `stats` includes some statistics of nodes. Feel free to explore them in the console.


#### 版权声明 | Copyright disclaimer

本项目仅用于演示和研究目的。内容版权归ZUN所有。

##### 相关百科网站 | TouHou wikis
[萌娘百科万物皆可萌的百科全书- zh.moegirl.org.cn - 东方Project](https://zh.moegirl.org.cn/%E4%B8%9C%E6%96%B9Project)
[以专业性为目标的东方Project维基百科](https://thwiki.cc/)

##### 原項目 | Similar project
[原神人物网络图 / social network graph of Genshin character](https://github.com/King-of-Infinite-Space/genshin-social-network)
