# DB 設計

## user (利用アカウント)

| カラム名 | 日本語名 | 型           | 主キー | 外部キー | option         |
| -------- | -------- | ------------ | ------ | -------- | -------------- |
| id       | ID       | int          | 〇     |          | AUTO_INCREMENT |
| name     | 社員名   | varchar(50)  |        |          |                |
| kane     | ふりがな | varchar(150) |        |          |                |
| createAt | 登録日   | datetime     |        |          |                |
| updateAt | 更新日   | datetime     |        |          |                |

## company 　(取引先企業)

| カラム名 | 日本語名 | 型           | 主キー | 外部キー | option         |
| -------- | -------- | ------------ | ------ | -------- | -------------- |
| id       | ID       | int          | 〇     |          | AUTO_INCREMENT |
| name     | 企業名   | varchar(150) |        |          |                |
| kane     | ふりがな | varchar(450) |        |          |                |
| createAt | 登録日   | datetime     |        |          |                |
| updateAt | 更新日   | datetime     |        |          |                |
