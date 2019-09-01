[![FOSSA Status](https://app.fossa.io/api/projects/git%2Bgithub.com%2Fyougg%2Fpool.svg?type=shield)](https://app.fossa.io/projects/git%2Bgithub.com%2Fyougg%2Fpool?ref=badge_shield)

### 简单Go线程池实现

线程池目前实现：
- Array blocking queue有界队列, 超过队列容量时新工作入队直接失败
- Linked blocking queue无界队列, 新工作入队时一直等待直到入队成功
- 同步阻塞队列与优先级队列待实现

使用方式见`pool_test.go`

## License
[![FOSSA Status](https://app.fossa.io/api/projects/git%2Bgithub.com%2Fyougg%2Fpool.svg?type=large)](https://app.fossa.io/projects/git%2Bgithub.com%2Fyougg%2Fpool?ref=badge_large)