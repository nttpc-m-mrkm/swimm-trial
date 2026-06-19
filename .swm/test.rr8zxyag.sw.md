---
title: test
---
<SwmSnippet path="/src/TaskService.java" line="22">

---

Swimmドキュメント追加

```java
    public Task createTask(String title, String description) {
        Task task = new Task();
        task.setTitle(title);
        task.setDescription(description);
        task.setStatus(TaskStatus.TODO);
        return taskRepository.save(task);
    }
```

---

</SwmSnippet>

<SwmMeta version="3.0.0" repo-id="Z2l0aHViJTNBJTNBc3dpbW0tdHJpYWwlM0ElM0FudHRwYy1tLW1ya20=" repo-name="swimm-trial"><sup>Powered by [Swimm](https://app.swimm.io/)</sup></SwmMeta>
