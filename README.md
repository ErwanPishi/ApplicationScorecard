# ApplicationScorecard
使用toad制作申请卡信用评分卡（用到征信变量衍生）

首先证明一个疑惑：

<img width="859" alt="截屏2023-08-15 09 44 21" src="https://github.com/ErwanPishi/ApplicationScorecard/assets/136585409/fdcb0fa4-aa07-4836-bfd2-2efe7b00b98f">

本次申请卡子模型是用于评价客户的稳定性，用到的指标全部来自征信变量衍生</br></br></br>
入模变量：手机号码更新次数、近15个月居住地址更新次数、最早一次手机号码信息更新日期距今天数、职业信息更新的最大时间间隔、最近一次更新的居住状态（代表稳定性）</br></br></br>
变量池：近X个月(工作单位,居住地址,手机号码)的【平均】更新次数</br>(职业、居住地、手机号码)(最近、最早)(更新的时间、更新时间距今天数、更新时间距今月数)</br>,最近一次更新的(职称、行业、职业、单位性质)</br>,  (职业、居住地址、手机号码)(更新日期的最大、最小、平均)时间间隔</br></br></br>
