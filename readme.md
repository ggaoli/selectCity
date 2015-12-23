# 地区三级联动下拉选择 
这是一款中国地区三级联动下拉选择插件，通过省份、城市、区县的联动选择，定位所在地区。
##兼容性
- ie6+
- 主流浏览器
##插件文件介绍
  - jquery-1.9.1.min.js：插件使用的依赖文件
  - jquery.select-city.js：插件的中心文件
  - allareas.json：插件的数据文件
##插件使用
###1、插件文件引用
    <script src="javascript/jquery-1.9.1.min.js"></script>
    <script src="javascript/jquery.select-city.js"></script>
###2、html中代码的实现
- 必要className介绍
 `area-select` ：插件外层容器
 `city-province`：省份
 `city-city`：市区
 `city-district`：县级
- 在html中给元素添加class示例
   
         <div class="area-select">
            <span class="all">所在地区:</span>
            <div class="split">
                <select class="city-province" name="province"></select>
            </div>
            <div class="split">
                <select class="city-city" name="city"></select>
            </div>
            <div class="split">
                <select class="city-district" name="district"></select>
             </div>
         </div>
- 插件的初始化
   
          $('.area-select').initArea('javascript/allareas.json'); 

##demo演示
#更新日志
- 实现省份、城市、区县三级联动，兼容ie6

    
  

  





