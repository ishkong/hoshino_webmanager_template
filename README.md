# Hoshino_WebManager_template
A template for Hoshino Services Web Manager

**本项目仅为模板，请配合插件使用**
**This project is only a template, please use it with plugins**

## 如何使用 How to use 

### 使用HTTPS且反向代理 HTTPS and use reverse proxy 

1. 下载并根据版本替换文件 Download and replace files

2. 重启Hoshino Restart Hoshino

### 使用HTTPS但没有反向代理 HTTPS but no reverse proxy

1. 下载文件 Download files

2. 在***所有***'{{public_address}}'后添加':{{port}}' Add ':{{port}}' after ***ALL*** '{{public_address}}' in files

3. 根据版本替换文件 Replace files

4. 重启Hoshino Restart Hoshino

### 使用HTTP但有反向代理 HTTP but use reverse proxy

1. 下载文件 Download files

2. 将***所有***'https'替换为'http' Replace ***ALL*** 'https' with 'http' in files

3. 删去'base.html'中注释所标记内容 Delete the content marked by the comment in 'base.html'

4. 根据版本替换文件 Replace files

5. 重启Hoshino Restart Hoshino

### 使用HTTP且没有反向代理 HTTP and no reverse proxy

1. 下载文件 Download files

2. 根据***所有***文件的注释修改 Find ***ALL*** notes and follow the notes

3. 根据版本替换文件 Replace files

4. 重启Hoshino Restart Hoshino

#### 可能涉及的文件及行数 Possible file locations

| File Name | Line |
| :----: | :----: |
| view.py | 111 |
| base.html | 8 |
| by_group.html | 28 |
| by_service.html | 26 |
| group_services.html | 55 |
| service_groups.html | 95 |
