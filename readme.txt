Путь файла который нужно запустить: NTI_project\NTI_project\bin\Debug\NTI_project.exe
В программе есть 5 видов пользователя: клиент, менеджер, курьер, работник склада и администратор
При открытии программы появится меню, с выбором вида пользователя. После этого программа предлагает войти в определенную учетную запись.
Учетные записи сотрудников создаются администратором. Данные для входа в учетную запись администратора: логин - admin , пароль - admin .
Учетную запись клиента может создать сам клиент пройдя процедуру регистрации.
Логика программы. 
Зарегистрированным пользователем создается заявка на заказ. Затем эту заявку рассматривает менеджер, который сам выбирает какие заказы брать под свою ответственность.
После подтверждения заявки менеджером и отправки заказа на выполнение, заказ попадает в список свободных заказов для курьера с целью забора.
Свободный курьер может выбрать данный заказ для выполнения забора. После он доставляет текущую посылку на склад, где работник склада может принять данный заказ на укомплектацию. Как только заказ будет укомплектован, он перенаправляется в список курьеров с целью доставки.
Свободный курьер берет на себя доставку текущего заказа, по завершению которого он помечает посылку доставленной получателю.