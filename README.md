# hixtrip 

## 需求
实现一个标准电商平台的一个下单功能 

1. 完整实现一个下单功能，包含以下功能：查询SKU价格(模拟，不需要实现)，扣减库存，支付(模拟,不需要实现,但要处理结果回调), 生成订单
2. 围绕下单功能，设计相关业务库表结构，并生成mybatis代码, 至少包括库存、订单

## 技术要求
1. 基于基础代码实现，要求理解DDD思想, 按示例要求(注意看代码注释和TODO)分层实现下单业务。
2. 领域服务已定义, 请注意看代码注释, 并在APP层进行调用。
3. 基础设施层限制使用mybatis\spring data redis实现。
4. 不考虑事务及分布式事务。
5. resources/sql中给出建表语句，包含索引设计。