![image](https://github.com/user-attachments/assets/5d77cfd0-568c-4980-a114-8f7d8718c896)
**КОД:**
```
local groups = ["ИКБО-" + std.str(x) + "-20" for x in std.range(1, 25)];
local createStudent(age, group, name) = {
   age: age,
   group: group,
   name: name
};
local students = 
[
createStudent(19, "ИКБО-4-20", "Иванов И.И."),
createStudent(18, "ИКБО-5-20", "Петров П.П."),
createStudent(18, "ИКБО-5-20", "Сидоров С.С."),
createStudent(19, "ИКБО-1-20", "Хайруллин Д.Л.")];
{
  groups: groups,
  students: students,
  subject: "Конфигурационное управление"
}

```
