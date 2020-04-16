








## User
##### POST /api/v1/login Login

#### Скрытая регистрация, отличается от основной преимущественно отсутствием обязательного referrer'a
##### POST /api/v1/register-hidden Register, но без поля 
#### Регистрация для пользователей
##### POST /api/v1/register Register 
##### GET /api/v1/me InstagramAccount информация о текущем пользователе
##### GET /api/v1/loginas/:id войти под пользователем

## смена пароля
### запросить
#### POST /api/v1/recovery/ask RecoveryAsk

### проверить код
#### POST /api/v1/recovery/validate RecoveryValidate

### сменить пароль
#### POST /api/v1/recovery/recover RecoveryRecover


## фидбек
#### POST /api/v1/tickets   NewTicket
#### GET /api/v1/ticket/:id Ticket
#### GET /api/v1/tickets []Ticket
#### POST /api/v1/ticket/:id/messages NewTicketMessage
#### GET /api/v1/ticket/:id/messages TicketMessage
#### POST /api/v1/tickets/:id/close -

 
# Инстаграм
### Subjects (тематики)
#### GET /api/v1/subjects []Subject
~~Авторизоваться с помощью инстаграма~~ не актуально
~~#### GET /api/v1/instagram/auth~~
### Форма для регистрации инстаграм аккаунта
#### POST /api/v1/fill-instagram-form InstagramForm
### Первое обязательное задание (выбрать 12 человек)
#### GET /api/v1/instagram/twelve/:instagram_account_id []InstagramAccount
