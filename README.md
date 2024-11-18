## 记录PR的历史，按照时间线排序，按照等级标注Meaningful的程度。(SABCDEF,X代表无需在意意义。)

---

|index|repo|url|level|ps|
|:-----:|:------:|-----------------|:-------:|:---------:|
|1|RimoChan/Vtuber_Tutorial|[新版本pyaml需要Loader参数。  opencv相机初始化缓慢。](https://github.com/RimoChan/Vtuber_Tutorial/pull/14)|C| 第一次PR,perf大提升|
|2|SigureMo/nyakku.moe|[🔗 chore: add friend link from @MrXnneHang #217](https://github.com/SigureMo/nyakku.moe/pull/217)|X|交换友链,第一次区分了core和chore|
|3|PaddlePaddle/Paddle|[fix: typo in dimension error message  recevied -> received #68989](https://github.com/PaddlePaddle/Paddle/pull/68989)|F-|纯水，修改单词.|
|4|PaddlePaddle/Paddle|[【Paddle Tensor No.21】：新增 bitwise_invert，复用已有接口 Tenos---r.__invert__ -part #69197](https://github.com/PaddlePaddle/Paddle/pull/69197)|A-|复用已有接口，本身没啥意义，但我第一次正经PR,一帮大佬喂饭，感谢，加分。|
|5|PaddlePaddle/docs|[【Paddle Tensor No.21】docs: Add docs for Tensor.bitwise_invert #6932](https://github.com/PaddlePaddle/docs/pull/6932#event-15244677592)|C|Paddle的docstring是rst可以转换到html和COPY-FROM.格式要求严格
|6|PaddlePaddle/Paddle|[【Paddle Tensor No.22】: 新增 paddle.less Tensor.less #69270](https://github.com/PaddlePaddle/Paddle/pull/69270)|C+|学会了用as的方式来直接来创建别名|
|7|PaddlePaddle/Paddle|[【Paddle Tensor No.13】: 新增paddle.positive和Tensor.__pos__ #69256](https://github.com/PaddlePaddle/Paddle/pull/69256)|B-|自己学着numpy加了一个positive,多做一些。|
|8|PaddlePaddle/Paddle|[【Paddle Tensor No.8、9、14、15】:为Tensor新增`__rshift__`,`__lshift__`,`__rlshift__`,`__rrshift__`#69348](https://github.com/PaddlePaddle/Paddle/pull/69348)|B+|大致区分编译时和运行时的方法import以及什么时候可能失败,完成一半,再把AutoTensor算子定义出来直接A|
|9|PaddlePaddle/Paddle|[【Typos】 Add Typos to pre-commit #69434](https://github.com/PaddlePaddle/Paddle/pull/69434#event-15325293073)|A-|理解了pre-commit以及学会了pre-commit-hook的自定义|


---

太累了，我也需要做一个AutoTable才行。<br>