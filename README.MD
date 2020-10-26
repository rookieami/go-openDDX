### 订单侠接口调用工具
```go
package go_openDDX

import (
	"fmt"
	"testing"
)

func init()  {
	AppKey=""//平台个人中心获取
	AppSecret="" //
}
func TestExcute(t *testing.T) {
	url:="" //接口地址
	res,err:=Excute("POST",url,Parameter{
	})
	if err != nil {
		fmt.Println(err)
	}
	fmt.Println(res)
}

```