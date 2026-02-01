# D008_government_3D 3D知识图谱问答+vue+django+neo4j基于知识图谱的政务服务问答系统

> 完整项目收费，可联系QQ: 81040295 微信: mmdsj186011 注明从git来的，谢谢！
也可以关注我的B站： 麦麦大数据 https://space.bilibili.com/1583208775
> 

关注B站，有好处！
编号:  D008 3D
## 视频
[video(video-97KYzRqH-1757662608184)(type-bilibili)(url-https://player.bilibili.com/player.html?aid=610510053)(image-https://i-blog.csdnimg.cn/img_convert/b79be60be369bf936b360e6284f6082c.jpeg)(title-vue+django+neo4j政府一网通办知识图谱数据分析系统)]
## 1 系统简介
系统简介：本系统是一个基于Vue.js和Django框架构建的知识图谱管理与可视化平台，采用Neo4j图数据库存储和处理数据。系统分为游客模式和管理员模式，游客用户无需登录即可访问和使用知识图谱的基本功能，而管理员需要登录后才能进行高级操作。系统的核心功能包括知识图谱的可视化展示、搜索、下载、词云生成、推荐功能以及3D知识图谱展示和基于LTP模型的简单政务问答功能，管理员还可以对知识图谱进行增删改查操作，并进行热门事务的可视化分析。通过前后端分离的架构设计，系统实现了高效的数据交互和用户友好的界面体验，为用户提供了直观、便捷的知识图谱管理与分析服务。
## 2 功能设计
系统功能分为两大模块：游客功能和管理员功能。游客功能包括搜索知识图谱事务，支持关键词搜索并聚焦显示相关内容；查看知识图谱，支持滑动和点击探索；下载知识图谱，提供便捷的导出功能；查看词云，展示关键字分布；推荐功能，在搜索框下方显示相关推荐内容；3D知识图谱展示，提供多角度和深度的图谱视图；以及基于LTP模型的简单政务问答功能，解答用户相关问题。管理员功能则包含知识图谱的管理，支持增删改查操作；热门事务的可视化分析，提供数据处理和图表展示；以及个人信息管理，允许管理员修改登录账号信息。系统通过Neo4j数据库高效存储和查询图数据，结合Vue.js的动态交互和Django的后端处理能力，为用户提供了一个功能齐全、操作便捷的知识图谱平台。
### 2.1系统架构图
![在这里插入图片描述](https://i-blog.csdnimg.cn/direct/7685af6dd4ab4c5d904df837f8c59394.png)
### 2.2 功能模块图
![在这里插入图片描述](https://i-blog.csdnimg.cn/direct/508daa924aa74fe8a05f30bead79df12.png)
### 2.3 需求文档
![在这里插入图片描述](https://i-blog.csdnimg.cn/direct/b4d7e41067564e45903acadd61acda7d.png)
### 2.4 技术文档
![在这里插入图片描述](https://i-blog.csdnimg.cn/direct/96ae5d83f83549e09c4c0aa84afaa137.png)
## 3 功能展示
### 3.1 登录 & 注册
![在这里插入图片描述](https://i-blog.csdnimg.cn/direct/e480ca8559944ab7a9d2b98428bd0632.png)
![在这里插入图片描述](https://i-blog.csdnimg.cn/direct/0eb9fe4a5d254fadbe9641d63ab93f9a.png)
### 3.2 主页
展示政务事项信息，支持搜索：
![在这里插入图片描述](https://i-blog.csdnimg.cn/direct/1f886a2d013a4d83a7bf8977ce046d46.png)

### 3.3 政务可视化
利用echarts图形对政务事项信息进行各个角度的分析，比如办理次数、收费情况：
![在这里插入图片描述](https://i-blog.csdnimg.cn/direct/d958715d79df492ab197263025a01552.png)

### 3.4 词云分析
政务信息词云分析
![在这里插入图片描述](https://i-blog.csdnimg.cn/direct/715b71edd893457dba1f5190e59c5152.png)
### 3.5 知识图谱可视化 和 查询
对政务信息提取为知识图谱，保存到neo4j数据库之中,前端实现可视化，支持模糊查询：
![在这里插入图片描述](https://i-blog.csdnimg.cn/direct/9403394781ab45a5aea3ef2921e2a541.png)

模糊查询：
![在这里插入图片描述](https://i-blog.csdnimg.cn/direct/2af4e51ce4f9498fb1bf6b885570b335.png)
### 3.6 3D知识图谱
基于3D的知识图谱可视化和搜索：
![在这里插入图片描述](https://i-blog.csdnimg.cn/direct/28196d50ae0b4e0d9c58b988054ad0c6.png)
### 3.7 政务问答
基于LTP模型识别实体+知识图谱匹配的政务问答：
![在这里插入图片描述](https://i-blog.csdnimg.cn/direct/b32a456ce0fc451b8f015a0cff3860dc.png)
### 3.6 知识图谱管理 
知识节点管理：增加、修改、删除
![在这里插入图片描述](https://i-blog.csdnimg.cn/direct/8891ccb66a1b4ecb9017e9e094316907.png)

关系管理：增加、修改、删除
![在这里插入图片描述](https://i-blog.csdnimg.cn/direct/74abd90c4e58485081c97b9530ef0212.png)
### 3.7 个人信息 
个人信息的修改、头像的修改：
![在这里插入图片描述](https://i-blog.csdnimg.cn/direct/0ce4d3a4210543eea1b113ce1f15db75.png)
修改密码

![在这里插入图片描述](https://i-blog.csdnimg.cn/direct/105104b4e84c4c908c236b9e6c3f3490.png)
## 4程序代码
### 4.1 代码说明
代码介绍：政府政务知识图谱可视化功能基于Python后端实现，通过构建政务实体（如政策、部门、法规）及关系的数据图谱，提供交互式可视化界面。该功能利用Neo4j或NetworkX存储和查询图谱数据，使用Flask/Django框架提供API服务，前端通过ECharts或D3.js渲染力导向图，展示实体间的关联（如政策引用、部门隶属），支持搜索、筛选和动态聚焦，帮助用户直观理解政务知识结构，提升决策效率和透明度。核心包括数据建模、图数据库集成、RESTful API和可视化渲染。
### 4.2 流程图
![在这里插入图片描述](https://i-blog.csdnimg.cn/direct/a1060ea6443f4549b96c0811d4d9adb2.png)
### 4.3 代码实例
```python
from flask import Flask, jsonify, request
from py2neo import Graph
import json

app = Flask(__name__)

# 连接Neo4j图数据库
graph = Graph("bolt://localhost:7687", auth=("neo4j", "password"))

@app.route('/api/knowledge_graph', methods=['GET'])
def get_knowledge_graph():
    # 从请求获取参数，如搜索词或筛选条件
    search_term = request.args.get('search', '')
    
    # Cypher查询示例：查找实体及关系
    query = """
    MATCH (n)-[r]->(m)
    WHERE n.name CONTAINS $search_term OR m.name CONTAINS $search_term
    RETURN n, r, m
    LIMIT 100
    """
    result = graph.run(query, search_term=search_term).data()
    
    # 处理结果为前端可用的JSON格式
    nodes = []
    links = []
    node_ids = set()
    
    for record in result:
        n = record['n']
        m = record['m']
        r = record['r']
        
        if n.identity not in node_ids:
            nodes.append({"id": n.identity, "name": n.get('name', 'Unknown'), "type": list(n.labels)[0]})
            node_ids.add(n.identity)
        if m.identity not in node_ids:
            nodes.append({"id": m.identity, "name": m.get('name', 'Unknown'), "type": list(m.labels)[0]})
            node_ids.add(m.identity)
        
        links.append({"source": n.identity, "target": m.identity, "relation": type(r).__name__})
    
    return jsonify({"nodes": nodes, "links": links})

if __name__ == '__main__':
    app.run(debug=True)

```
