# Общее про систему выдачи ролей

---

!!! info "Параметры системы"
    - `role_request_channel` - канал, в который будет приходить запрос на выдачу роли
    - `organizational_roles` - организационные роли
    - `illegal_roles` - роли нелегальных организаций

    При вводе нелегальных организаций в компоненте [SendRoleRequestView](../components/role_requests.md#sendrolerequestview) добавляется еще один селектор

!!! info "Настройка"
    Все параметры настраиваются с помощью команды `/config other setup` [здесь](../commands/config.md#config-other-setup)