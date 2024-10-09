## 1.1.1 付费/定制版

- 新增nbt模块
- 更新TabooLib版本
- 新增内置粒子函数

```java line-numbers
public static void spawnParticle(Location location, Player player, Particle particle, Vector offset, double speed, int count, Object data) {
}

public static void createLotus(Player player, String particleName, long period, Vector vector, int count, double speed, ProxyParticle.Data data) {
}

public static void createArc(Player player, String particleName, double startAngele, double angle, double radius, double step, long period, Vector vector, int count, double speed, ProxyParticle.Data data) {
}

public static void createAstroid(Player player, String particleName, double radius, Vector vector, int count, double speed, ProxyParticle.Data data) {
}

public static void createCircle(Player player, String particleName, double radius, double step, long period, Vector vector, int count, double speed, ProxyParticle.Data data) {
}

public static void createCube(Player player, String particleName, Location minLoc, Location maxLoc, double step, Vector vector, int count, double speed, ProxyParticle.Data data) {
}

public static void createFilledCircle(Player player, String particleName, double radius, int sample, Vector vector, int count, double speed, ProxyParticle.Data data) {
}

public static void createHeart(Player player, String particleName, double xScaleRate, double yScaleRate, long period, Vector vector, int count, double speed, ProxyParticle.Data data) {
}

public static void createLine(Player player, String particleName, Location end, double step, long period, Vector vector, int count, double speed, ProxyParticle.Data data) {
}

public static void createNRankBezierCurve(Player player, String particleName, List<Location> locations, double step, Vector vector, int count, double speed, ProxyParticle.Data data) {
}

public static void createNStar(Player player, String particleName, int corner, double radius, double step, Vector vector, int count, double speed, ProxyParticle.Data data) {
}

public static void createOctagonalStar(Player player, String particleName, double radius, double step, Vector vector, int count, double speed, ProxyParticle.Data data) {
}

public static void createPolygon(Player player, String particleName, int side, double step, Vector vector, int count, double speed, ProxyParticle.Data data) {
}

public static void createPyramid(Player player, String particleName, int side, double radius, double height, double step, Vector vector, int count, double speed, ProxyParticle.Data data) {
}

public static void createRay(Player player, String particleName, Vector direction, double maxLength, double step, double range, String stopType, long period, Vector vector, int count, double speed, ProxyParticle.Data data) {
}

public static void createSphere(Player player, String particleName, int sample, double radius, Vector vector, int count, double speed, ProxyParticle.Data data) {
}

public static void createStar(Player player, String particleName, double radius, double step, long period, Vector vector, int count, double speed, ProxyParticle.Data data) {
}

public static void createThreeRankBezierCurve(Player player, String particleName, Location p0, Location p1, Location p2, Location p3, double step, Vector vector, int count, double speed, ProxyParticle.Data data) {
}

public static void createTwoRankBezierCurve(Player player, String particleName, Location p0, Location p1, Location p2, double step, Vector vector, int count, double speed, ProxyParticle.Data data) {
}
```

- 统一了提示
- 更新了验证版本
- 新增PlaceholderAPI的相关变量扩展
    - 淬炼的最高等级
        - > %CSXPlaceholder_Tempering_maxTemperingLevel%
    - 一共淬炼了多少次
        - > %CSXPlaceholder_Tempering_temperingAmount%
    - 淬炼成功了多少次
        - > %CSXPlaceholder_Tempering_temperingSuccessAmount%
    - 淬炼失败了多少次
        - > %CSXPlaceholder_Tempering_temperingFailAmount%
    - 用某个淬炼石淬炼成功了多少次
        - > %CSXPlaceholder_Tempering_temperingStoneSuccessAmount_淬炼石名称%
    - 用某个淬炼石淬炼失败了多少次
        - > %CSXPlaceholder_Tempering_temperingStoneFailAmount_淬炼石名称%
- 更新给予淬炼石/保护符的方法
- 更新淬炼UI
- 更新移星UI
- 更新部分指令预览UI
- 更新Info系指令在后台的输出效果
- 优化指令补全效果
- 优化淬炼石加载速度
- 取消指令stones和protects，融合进指令stone以及protect
- 配置生成器支持了重载
- 不用输入参数的指令支持了点击执行，有参数的支持了点击键入指令
- 新增指令查询手持物品NBT
- 新增Debug日记
- 新增更多输出信息
- 新增BungeeCord跨服淬炼消息
- 插件构造改变(多模块化)