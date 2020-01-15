








## User
##### POST /api/v1/login Login
##### POST /api/v1/register-hidden RegisterHidden  скрытая регистрация
##### POST /api/v1/register Register   регистрация для пользователей
##### GET /api/v1/me Me информация о текущем пользователе


## Subjects
##### GET /api/v1/subjects []Subject


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

 

