# 全局公共参数

**全局Header参数**

| 参数名 | 示例值 | 参数类型 | 是否必填 | 参数描述 |
| --- | --- | ---- | ---- | ---- |
| 暂无参数 |

**全局Query参数**

| 参数名 | 示例值 | 参数类型 | 是否必填 | 参数描述 |
| --- | --- | ---- | ---- | ---- |
| 暂无参数 |

**全局Body参数**

| 参数名 | 示例值 | 参数类型 | 是否必填 | 参数描述 |
| --- | --- | ---- | ---- | ---- |
| 暂无参数 |

**全局认证方式**

> 无需认证

# 状态码说明

| 状态码 | 中文描述 |
| --- | ---- |
| 暂无参数 |

# companies

> 创建人: 阿尔刻

> 更新人: 阿尔刻

> 创建时间: 2026-03-11 09:52:51

> 更新时间: 2026-03-11 10:14:25

```text
暂无描述
```

**目录Header参数**

| 参数名 | 示例值 | 参数类型 | 是否必填 | 参数描述 |
| --- | --- | ---- | ---- | ---- |
| 暂无参数 |

**目录Query参数**

| 参数名 | 示例值 | 参数类型 | 是否必填 | 参数描述 |
| --- | --- | ---- | ---- | ---- |
| 暂无参数 |

**目录Body参数**

| 参数名 | 示例值 | 参数类型 | 是否必填 | 参数描述 |
| --- | --- | ---- | ---- | ---- |
| 暂无参数 |

**目录认证信息**

> 无需认证

**Query**

## 企业基本信息列表查询

> 创建人: 阿尔刻

> 更新人: 阿尔刻

> 创建时间: 2026-03-11 09:52:51

> 更新时间: 2026-03-11 10:12:48

```text
暂无描述
```

**接口状态**

> 开发中

**接口URL**

> https://api-portal.sinexcel.com:8901/srm-tools-s2272-1/v1/0/tianyancha-companies?id=1

**请求方式**

> GET

**Content-Type**

> json

**请求Header参数**

| 参数名 | 示例值 | 参数类型 | 是否必填 | 参数描述 |
| --- | --- | ---- | ---- | ---- |
| Accept | */* | string | 否 | - |
| Authorization | Bearer 198c1326-9aff-43cb-9b57-52eb39dd27f8 | string | 是 | - |

**请求Query参数**

| 参数名 | 示例值 | 参数类型 | 是否必填 | 参数描述 |
| --- | --- | ---- | ---- | ---- |
| actualCapital | string | string | 否 | 实缴资本 |
| actualCapitalCurrency | string | string | 否 | 实缴资本币种 |
| alias | string | string | 否 | 简称 |
| approvedTime | 1985-04-06T05:59:54.965Z | string | 否 | 核准日期 |
| base | string | string | 否 | 数据来源地 |
| bondName | string | string | 否 | 股票名称 |
| bondNum | string | string | 否 | 股票代码 |
| bondType | string | string | 否 | 股票类型 |
| brnNumber | string | string | 否 | 工商注册号 |
| businessScope | string | string | 否 | 经营范围 |
| businessTermEnd | 1985-04-06T05:59:54.965Z | string | 否 | 营业期限结束 |
| businessTermStart | 1985-04-06T05:59:54.965Z | string | 否 | 营业期限开始 |
| cancelDate | 1985-04-06T05:59:54.965Z | string | 否 | 注销日期 |
| cancelReason | string | string | 否 | 注销原因 |
| city | string | string | 否 | 城市 |
| companyOrgType | string | string | 否 | 企业类型 |
| companyType | 7131 | string | 否 | 类型 |
| createdBy | 5549 | string | 否 | 创建人 |
| creationDate | 1985-04-06T05:59:54.965Z | string | 否 | 创建时间 |
| creditCode | string | string | 否 | 统一社会信用代码 |
| dataSource | string | string | 否 | 数据来源 |
| district | string | string | 否 | 区县 |
| email | string | string | 否 | 邮箱 |
| englishName | string | string | 否 | 英文名 |
| establishTime | 1985-04-06T05:59:54.965Z | string | 否 | 成立日期 |
| historyNames | string | string | 否 | 曾用名 |
| id | 1 | string | 否 | 主键ID |
| industry | string | string | 否 | 行业 |
| isMicroEnt | 7131 | string | 否 | 是否小微企业 |
| lastUpdateDate | 1985-04-06T05:59:54.965Z | string | 否 | 最后更新时间 |
| lastUpdatedBy | 5549 | string | 否 | 最后更新人 |
| legalPersonName | string | string | 否 | 法定代表人 |
| name | string | string | 否 | 企业名称 |
| objectVersionNumber | 5549 | string | 否 | 版本号 |
| orgNumber | string | string | 否 | 组织机构代码 |
| percentileScore | 7131 | string | 否 | 评分 |
| phoneNumber | string | string | 否 | 电话 |
| province | string | string | 否 | 省份 |
| regCapital | string | string | 否 | 注册资本 |
| regCapitalCurrency | string | string | 否 | 注册资本币种 |
| regInstitute | string | string | 否 | 登记机关 |
| regLocation | string | string | 否 | 注册地址 |
| regNumber | string | string | 否 | 注册号 |
| regStatus | string | string | 否 | 登记状态 |
| revokeDate | 1985-04-06T05:59:54.965Z | string | 否 | 吊销日期 |
| revokeReason | string | string | 否 | 吊销原因 |
| socialStaffNum | 7131 | string | 否 | 员工人数 |
| staffNumRange | string | string | 否 | 员工人数范围 |
| tags | string | string | 否 | 标签 |
| taxNumber | string | string | 否 | 纳税人识别号 |
| tianyanchaId | 5549 | string | 否 | 天眼查企业ID |
| usedBondName | string | string | 否 | 曾用股票名称 |
| websiteList | string | string | 否 | 网址 |

**请求Body参数**

```javascript
暂无数据
```

**认证方式**

> 无需认证

**响应示例**

* 成功(200)

```javascript
{
	"totalPages": 1,
	"totalElements": 1,
	"numberOfElements": 1,
	"size": 20,
	"number": 0,
	"content": [
		{
			"id": 1,
			"name": "中航重机股份有限公司",
			"creditCode": "91520000214434146R",
			"legalPersonName": "姬苏春",
			"regStatus": "存续",
			"regCapital": "77800.32万人民币",
			"actualCapital": "77800.32万人民币",
			"regCapitalCurrency": "人民币",
			"actualCapitalCurrency": "人民币",
			"businessScope": "法律、法规、国务院决定规定禁止的不得经营；法律、法规、国务院决定规定应当许可（审批）的，经审批机关批准后凭许可（审批）文件经营;法律、法规、国务院决定规定无需许可（审批）的，市场主体自主选择经营。（股权投资及经营管理；军民共用液压件、液压系统、锻件、铸件、换热器、飞机及航空发动机附件，汽车零备件的研制、开发、制造、修理及销售；经营本企业自产机电产品、成套设备及相关技术的出口业务；经营本企业生产、科研所需的原辅材料、机械设备、仪器仪表、备品备件、零配件及技术的进口业务；开展本企业进料加工和“三来一补”业务。液压、锻件、铸件、换热器技术开发、转让和咨询服务；物流；机械冷热加工、修理修配服务。）",
			"regLocation": "贵州双龙航空港经济区机场路9号太升国际A栋3单元5层",
			"regInstitute": "贵阳市市场监督管理局贵州双龙航空港经济区分局",
			"companyOrgType": "其他股份有限公司(上市)",
			"industry": "汽车制造业",
			"city": "毕节市",
			"district": "威宁彝族回族苗族自治县",
			"phoneNumber": "0851-88600765",
			"email": "zhzj@avic.com",
			"websiteList": "www.hm.avic.com",
			"bondName": "中航重机",
			"bondNum": "600765",
			"bondType": "A股",
			"orgNumber": "214434146",
			"taxNumber": "91520000214434146R",
			"regNumber": "520000000005018",
			"socialStaffNum": 9023,
			"staffNumRange": "5000-9999人",
			"tags": "企业集团;存续;融资轮次;上市信息;项目品牌;投资机构;曾用名",
			"historyNames": "贵州力源液压股份有限公司;",
			"alias": "中航重机",
			"percentileScore": 9696,
			"isMicroEnt": 0,
			"cancelReason": "",
			"revokeReason": "",
			"brnNumber": "",
			"usedBondName": "力源液压->G力源->力源液压",
			"base": "gz",
			"creationDate": "2026-02-27 17:12:49",
			"createdBy": 2,
			"lastUpdateDate": "2026-02-27 17:12:49",
			"lastUpdatedBy": 2,
			"objectVersionNumber": 1
		}
	],
	"empty": false
}
```

* 失败(404)

```javascript
暂无数据
```

**请求Header参数**

| 参数名 | 示例值 | 参数类型 | 是否必填 | 参数描述 |
| --- | --- | ---- | ---- | ---- |
| Accept | */* | string | 否 | - |
| Authorization | Bearer 198c1326-9aff-43cb-9b57-52eb39dd27f8 | string | 是 | - |

**Query**

## 创建或更新企业基本信息

> 创建人: 阿尔刻

> 更新人: 阿尔刻

> 创建时间: 2026-03-11 09:52:51

> 更新时间: 2026-03-11 10:13:07

```text
暂无描述
```

**接口状态**

> 开发中

**接口URL**

> https://api-portal.sinexcel.com:8901/srm-tools-s2272-1/v1/0/tianyancha-companies

**请求方式**

> POST

**Content-Type**

> json

**请求Header参数**

| 参数名 | 示例值 | 参数类型 | 是否必填 | 参数描述 |
| --- | --- | ---- | ---- | ---- |
| Content-Type | application/json | string | 否 | - |
| Accept | */* | string | 否 | - |
| Authorization | Bearer 198c1326-9aff-43cb-9b57-52eb39dd27f8 | string | 是 | - |

**请求Body参数**

```javascript
[
	 {

      "name": "中航重机股份有限公司22",
      "creditCode": "91520000214434146R1",
      "legalPersonName": "姬苏春",
      "regStatus": "存续",
      "regCapital": "77800.32万人民币",
      "actualCapital": "77800.32万人民币",
      "regCapitalCurrency": "人民币",
      "actualCapitalCurrency": "人民币",
      "businessScope": "法律、法规、国务院决定规定禁止的不得经营；法律、法规、国务院决定规定应当许可（审批）的，经审批机关批准后凭许可（审批）文件经营;法律、法规、国务院决定规定无需许可（审批）的，市场主体自主选择经营。（股权投资及经营管理；军民共用液压件、液压系统、锻件、铸件、换热器、飞机及航空发动机附件，汽车零备件的研制、开发、制造、修理及销售；经营本企业自产机电产品、成套设备及相关技术的出口业务；经营本企业生产、科研所需的原辅材料、机械设备、仪器仪表、备品备件、零配件及技术的进口业务；开展本企业进料加工和“三来一补”业务。液压、锻件、铸件、换热器技术开发、转让和咨询服务；物流；机械冷热加工、修理修配服务。）",
      "regLocation": "贵州双龙航空港经济区机场路9号太升国际A栋3单元5层",
      "regInstitute": "贵阳市市场监督管理局贵州双龙航空港经济区分局",
      "companyOrgType": "其他股份有限公司(上市)",
      "industry": "汽车制造业",
      "city": "毕节市",
      "district": "威宁彝族回族苗族自治县",
      "phoneNumber": "0851-88600765",
      "email": "zhzj@avic.com",
      "websiteList": "www.hm.avic.com",
      "bondName": "中航重机",
      "bondNum": "600765",
      "bondType": "A股",
      "orgNumber": "214434146",
      "taxNumber": "91520000214434146R",
      "regNumber": "520000000005018",
      "socialStaffNum": 9023,
      "staffNumRange": "5000-9999人",
      "tags": "企业集团;存续;融资轮次;上市信息;项目品牌;投资机构;曾用名",
      "historyNames": "贵州力源液压股份有限公司;",
      "alias": "中航重机",
      "percentileScore": 9696,
      "isMicroEnt": 0,
      "cancelReason": "",
      "revokeReason": "",
      "brnNumber": "",
      "usedBondName": "力源液压->G力源->力源液压",
      "base": "gz"
  
    }
]
```

**认证方式**

> 无需认证

**响应示例**

* 成功(200)

```javascript
[
	{
		"id": 4,
		"name": "中航重机股份有限公司22",
		"creditCode": "91520000214434146R1",
		"legalPersonName": "姬苏春",
		"regStatus": "存续",
		"regCapital": "77800.32万人民币",
		"actualCapital": "77800.32万人民币",
		"regCapitalCurrency": "人民币",
		"actualCapitalCurrency": "人民币",
		"businessScope": "法律、法规、国务院决定规定禁止的不得经营；法律、法规、国务院决定规定应当许可（审批）的，经审批机关批准后凭许可（审批）文件经营;法律、法规、国务院决定规定无需许可（审批）的，市场主体自主选择经营。（股权投资及经营管理；军民共用液压件、液压系统、锻件、铸件、换热器、飞机及航空发动机附件，汽车零备件的研制、开发、制造、修理及销售；经营本企业自产机电产品、成套设备及相关技术的出口业务；经营本企业生产、科研所需的原辅材料、机械设备、仪器仪表、备品备件、零配件及技术的进口业务；开展本企业进料加工和“三来一补”业务。液压、锻件、铸件、换热器技术开发、转让和咨询服务；物流；机械冷热加工、修理修配服务。）",
		"regLocation": "贵州双龙航空港经济区机场路9号太升国际A栋3单元5层",
		"regInstitute": "贵阳市市场监督管理局贵州双龙航空港经济区分局",
		"companyOrgType": "其他股份有限公司(上市)",
		"industry": "汽车制造业",
		"city": "毕节市",
		"district": "威宁彝族回族苗族自治县",
		"phoneNumber": "0851-88600765",
		"email": "zhzj@avic.com",
		"websiteList": "www.hm.avic.com",
		"bondName": "中航重机",
		"bondNum": "600765",
		"bondType": "A股",
		"orgNumber": "214434146",
		"taxNumber": "91520000214434146R",
		"regNumber": "520000000005018",
		"socialStaffNum": 9023,
		"staffNumRange": "5000-9999人",
		"tags": "企业集团;存续;融资轮次;上市信息;项目品牌;投资机构;曾用名",
		"historyNames": "贵州力源液压股份有限公司;",
		"alias": "中航重机",
		"percentileScore": 9696,
		"isMicroEnt": 0,
		"cancelReason": "",
		"revokeReason": "",
		"brnNumber": "",
		"usedBondName": "力源液压->G力源->力源液压",
		"base": "gz"
	}
]
```

* 失败(404)

```javascript
暂无数据
```

**请求Header参数**

| 参数名 | 示例值 | 参数类型 | 是否必填 | 参数描述 |
| --- | --- | ---- | ---- | ---- |
| Content-Type | application/json | string | 否 | - |
| Accept | */* | string | 否 | - |
| Authorization | Bearer 198c1326-9aff-43cb-9b57-52eb39dd27f8 | string | 是 | - |

**Query**

## 删除企业基本信息

> 创建人: 阿尔刻

> 更新人: 阿尔刻

> 创建时间: 2026-03-11 09:52:51

> 更新时间: 2026-03-11 10:13:12

```text
暂无描述
```

**接口状态**

> 开发中

**接口URL**

> https://api-portal.sinexcel.com:8901/srm-tools-s2272-1/v1/0/tianyancha-companies

**请求方式**

> DELETE

**Content-Type**

> json

**请求Header参数**

| 参数名 | 示例值 | 参数类型 | 是否必填 | 参数描述 |
| --- | --- | ---- | ---- | ---- |
| Content-Type | application/json | string | 否 | - |
| Accept | */* | string | 否 | - |
| Authorization | Bearer 198c1326-9aff-43cb-9b57-52eb39dd27f8 | string | 是 | - |

**请求Body参数**

```javascript
[
	{
		"id":4
	}
]
```

**认证方式**

> 无需认证

**响应示例**

* 成功(200)

```javascript
暂无数据
```

* 失败(404)

```javascript
暂无数据
```

**请求Header参数**

| 参数名 | 示例值 | 参数类型 | 是否必填 | 参数描述 |
| --- | --- | ---- | ---- | ---- |
| Content-Type | application/json | string | 否 | - |
| Accept | */* | string | 否 | - |
| Authorization | Bearer 198c1326-9aff-43cb-9b57-52eb39dd27f8 | string | 是 | - |

**Query**

## 企业基本信息明细

> 创建人: 阿尔刻

> 更新人: 阿尔刻

> 创建时间: 2026-03-11 09:52:51

> 更新时间: 2026-03-11 10:13:17

```text
暂无描述
```

**接口状态**

> 开发中

**接口URL**

> https://api-portal.sinexcel.com:8901/srm-tools-s2272-1/v1/0/tianyancha-companies/:id

**请求方式**

> GET

**Content-Type**

> none

**请求Header参数**

| 参数名 | 示例值 | 参数类型 | 是否必填 | 参数描述 |
| --- | --- | ---- | ---- | ---- |
| Accept | */* | string | 否 | - |
| Authorization | Bearer 198c1326-9aff-43cb-9b57-52eb39dd27f8 | string | 是 | - |

**路径变量**

| 参数名 | 示例值 | 参数类型 | 是否必填 | 参数描述 |
| --- | --- | ---- | ---- | ---- |
| id | 1 | string | 是 | - |

**认证方式**

> 无需认证

**响应示例**

* 成功(200)

```javascript
{
	"id": 1,
	"name": "中航重机股份有限公司",
	"creditCode": "91520000214434146R",
	"legalPersonName": "姬苏春",
	"regStatus": "存续",
	"regCapital": "77800.32万人民币",
	"actualCapital": "77800.32万人民币",
	"regCapitalCurrency": "人民币",
	"actualCapitalCurrency": "人民币",
	"businessScope": "法律、法规、国务院决定规定禁止的不得经营；法律、法规、国务院决定规定应当许可（审批）的，经审批机关批准后凭许可（审批）文件经营;法律、法规、国务院决定规定无需许可（审批）的，市场主体自主选择经营。（股权投资及经营管理；军民共用液压件、液压系统、锻件、铸件、换热器、飞机及航空发动机附件，汽车零备件的研制、开发、制造、修理及销售；经营本企业自产机电产品、成套设备及相关技术的出口业务；经营本企业生产、科研所需的原辅材料、机械设备、仪器仪表、备品备件、零配件及技术的进口业务；开展本企业进料加工和“三来一补”业务。液压、锻件、铸件、换热器技术开发、转让和咨询服务；物流；机械冷热加工、修理修配服务。）",
	"regLocation": "贵州双龙航空港经济区机场路9号太升国际A栋3单元5层",
	"regInstitute": "贵阳市市场监督管理局贵州双龙航空港经济区分局",
	"companyOrgType": "其他股份有限公司(上市)",
	"industry": "汽车制造业",
	"city": "毕节市",
	"district": "威宁彝族回族苗族自治县",
	"phoneNumber": "0851-88600765",
	"email": "zhzj@avic.com",
	"websiteList": "www.hm.avic.com",
	"bondName": "中航重机",
	"bondNum": "600765",
	"bondType": "A股",
	"orgNumber": "214434146",
	"taxNumber": "91520000214434146R",
	"regNumber": "520000000005018",
	"socialStaffNum": 9023,
	"staffNumRange": "5000-9999人",
	"tags": "企业集团;存续;融资轮次;上市信息;项目品牌;投资机构;曾用名",
	"historyNames": "贵州力源液压股份有限公司;",
	"alias": "中航重机",
	"percentileScore": 9696,
	"isMicroEnt": 0,
	"cancelReason": "",
	"revokeReason": "",
	"brnNumber": "",
	"usedBondName": "力源液压->G力源->力源液压",
	"base": "gz",
	"creationDate": "2026-02-27 17:12:49",
	"createdBy": 2,
	"lastUpdateDate": "2026-02-27 17:12:49",
	"lastUpdatedBy": 2,
	"objectVersionNumber": 1
}
```

* 失败(404)

```javascript
暂无数据
```

**请求Header参数**

| 参数名 | 示例值 | 参数类型 | 是否必填 | 参数描述 |
| --- | --- | ---- | ---- | ---- |
| Accept | */* | string | 否 | - |
| Authorization | Bearer 198c1326-9aff-43cb-9b57-52eb39dd27f8 | string | 是 | - |

**Query**
