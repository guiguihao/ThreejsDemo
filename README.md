演示：https://guiguihao.github.io/ThreejsExamples/
## 开发环境设置

### 使用CDN方式（简单方式）
在HTML文件中直接引入Three.js:
```html
<script src="https://cdn.jsdelivr.net/npm/three@0.160.0/build/three.min.js"></script>
```



### 本地开发服务器
由于浏览器安全限制，直接打开本地HTML文件可能无法正常加载纹理等资源。
推荐使用以下方式启动本地服务器:

   使用VS Code的Live Server扩展:
   安装Live Server扩展后，右键HTML文件选择"使用Live Server打开"



## 4. 核心概念示例
### 4.1 场景(Scene)
- 创建和管理场景
- 场景图(Scene Graph)
- 场景背景和雾效

### 4.2 相机(Camera)
- 透视相机(PerspectiveCamera)
- 正交相机(OrthographicCamera)
- 相机控制和运动

### 4.3 渲染器(Renderer)
- WebGLRenderer基本用法
- 渲染循环
- 渲染配置和优化

### 4.4 几何体(Geometry)
- 基础几何体(立方体、球体、圆柱体等)
- BufferGeometry详解
- 自定义几何体创建

### 4.5 材质(Material)
- 基础材质类型(MeshBasicMaterial, MeshStandardMaterial等)
- 材质属性和纹理
- 自定义着色器材质(ShaderMaterial)

### 4.6 光照(Light)
- 环境光(AmbientLight)
- 方向光(DirectionalLight)
- 点光源(PointLight)
- 聚光灯(SpotLight)
- 半球光(HemisphereLight)

## 5. 进阶技术
### 5.1 纹理与材质
- 纹理加载和使用
- UV映射
- 法线贴图和凹凸贴图
- 环境贴图和反射

### 5.2 动画系统
- 基础动画循环
- 关键帧动画
- 骨骼动画
- GSAP与Three.js结合

### 5.3 粒子系统
- 点云(Points)
- 粒子动画
- 自定义粒子系统

### 5.4 交互控制
- OrbitControls使用
- TransformControls使用
- 射线检测(Raycaster)和对象拾取
- 鼠标和触摸事件处理

### 5.5 性能优化
- 实例化渲染(InstancedMesh)
- LOD(Level of Detail)技术
- 对象池和资源管理
- 渲染性能监控

## 6. 高级主题
### 6.1 后期处理
- EffectComposer使用
- 常见后期特效(泛光、景深等)
- 自定义后期处理着色器

### 6.2 物理引擎集成
- ammo.js集成
- cannon.js集成
- 碰撞检测和物理模拟

### 6.3 加载外部模型
- GLTF/GLB格式加载
- FBX格式加载
- 模型优化和处理

### 6.4 着色器编程
- GLSL基础
- 顶点着色器和片段着色器
- 自定义效果实现

### 6.5 AR/VR应用
- WebXR API基础
- Three.js与AR/VR结合
- 沉浸式交互体验

## 7. 实战项目
- **交互式产品展示**
- **3D数据可视化**




祝您学习愉快！
