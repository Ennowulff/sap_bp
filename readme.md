<img width="130" height="130" alt="image" src="https://github.com/user-attachments/assets/06b7ae0a-5153-4be0-8eef-9d29d5fd26c3" />


# SAP Business Partners

# General

Information about general flags, parameters, behaviour, ...

## Task modes
```
CONSTANTS c_task_insert                 TYPE bus_ei_object_task  VALUE 'I'  ##NO_TEXT.
CONSTANTS c_task_update                 TYPE bus_ei_object_task  VALUE 'U'  ##NO_TEXT.
CONSTANTS c_task_modify                 TYPE bus_ei_object_task  VALUE 'M'  ##NO_TEXT.
CONSTANTS c_task_delete                 TYPE bus_ei_object_task  VALUE 'D'  ##NO_TEXT.
CONSTANTS c_task_current_state          TYPE bus_ei_object_task  VALUE 'C'  ##NO_TEXT.
```
## Update flags
```
CONSTANTS c_updateflag_update           TYPE string              VALUE 'U'  ##NO_TEXT.
CONSTANTS c_updateflag_delete           TYPE string              VALUE 'D'  ##NO_TEXT.
CONSTANTS c_updateflag_insert           TYPE string              VALUE 'I'  ##NO_TEXT.
```
## Activities
```
CONSTANTS c_activity_create             TYPE bus_dialog-activity VALUE '01' ##NO_TEXT.
CONSTANTS c_activity_change             TYPE bus_dialog-activity VALUE '02' ##NO_TEXT.
CONSTANTS c_activity_display            TYPE bus_dialog-activity VALUE '03' ##NO_TEXT.
```
