# Checkbox-type-conversion
复选框选中数据转换为ios和android使用的list结构

                  "concernAreas": [
                    {
                        "id": "CA01", "name": "环境保护"
                    },{
                        "id": "CA02","name": "文化艺术"
                    },{
                        "id": "CA03","name": "卫生健康"
                    },{
                        "id": "CA04","name": "科学技术"
                    }, {
                        "id": "CA05","name": "交通安全"
                    }
                  ],
                  
## 设置自定义属性 data-**
    <label class="label"><input name="mark" type="checkbox" data-id="CA01" data-value="环境保护"/> 环境保护 </label>
    <label class="label"><input name="mark" type="checkbox" data-id="CA02" data-value="文化艺术"/> 文化艺术 </label>
    <label class="label"><input name="mark" type="checkbox" data-id="CA03" data-value="卫生健康"/> 卫生健康 </label>
    <label class="label"><input name="mark" type="checkbox" data-id="CA04" data-value="科学技术"/> 科学技术 </label>
    <label class="label"><input name="mark" type="checkbox" data-id="CA05" data-value="交通安全"/> 交通安全 </label>
    
    
## 获取自定义属性 
    each 循环遍历 $('input[name="mark"]:checked')复选框被选中的数据 
    v.getAttribute("data-id")
    v.getAttribute("data-value")
    
## 最后将数据放到 {  } 中，设置key和value即可
代码已经封装好了，详见demo。
