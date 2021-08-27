# -------- LuckPerms 权限组 --------  
`````` 
lp creategroup [权限组]   # 创建权限组</a></p>
lp listgroups   # 列出所有权限组 </a></p>
lp deletegroup <权限组>   # 删除权限组
lp user 玩家名称 permission set [权限]   # 给玩家设置权限
lp group default permission set - <权限> [true|false] [背景...]   # 给权限组设置权限
lp user _Beoo clear   # 清除玩家的使用权限
lp user _Beoo parent add default   # 让玩家继承权限组
lp user _Beoo parent addtemp 权限组 31d   # 将 _Beoo 拉入权限组31天
lp group default editor    # 开启编辑网页接口
lp group default setdisplayname <名称>    # 为 default 权限组设置显示名称
lp group default meta addprefix 100 [前缀]    # 为 default 权限组设置优先级 100 的前缀
lp group default meta removeprefix 100 [前缀]   # 为 default 权限组删除优先级 100 的前缀
`````` 
# -------- LuckPerms 权限组变量 --------  
`````` 
# %luckperms_primary_group_name%    # 权限组的显示名称
# %luckperms_prefix%    # 返回玩家的前缀
# %luckperms_suffix%    # 返回玩家的后缀
# %luckperms_group_expiry_time%   返回玩家临时继承权限组的剩余时间
`````` 











































