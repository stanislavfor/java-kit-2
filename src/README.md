# Java Development Kit (семинары)
## Урок 2. программные интерфейсы

### Домашнее задание<br><br>
- На семинаре мы разделили класс отвечающий за клиентское приложение на класс, отвечающий за логику приложения и за графическую часть приложения. А также создали слабую связь между ними с помощью интерфейса. 
- Аналогичным образом вам надо преобразовать серверную часть приложения. Схема, которую требуется реализовать, также есть в материалах к уроку.
- Вы можете работать со своим проектом из первой домашки, а можете работать с проектом с семинара (ссылка в материалах к уроку). 
- Требуется разделить класс серверного приложения на контроллер, GUI и репозиторий.
- Если вы работаете со своим проектом, то клиентскую часть также надо разделить на контроллер и GUI.
- Связь между составляющими проекта реализовать с помощью интерфейсов.
  

**Примечание**

- Контроллер (Controller) Java-проекта - это класс или набор классов, которые обрабатывают запросы от клиента и передают их соответствующим компонентам серверной части. 
Контроллер обеспечивает взаимодействие между клиентской и серверной частями приложения.
- GUI (Graphical User Interface) в Java-проекте - это графический пользовательский интерфейс, построенный на языке программирования или языке разметки и стилей. 
Он состоит из графических элементов, которые обеспечивают отображение и взаимодействие элементов интерфейса с пользователем. 
В проекте используется Swing (язык интерфейса Swing). 
Это язык программирования Java, который используется для создания графического интерфейса программ. 
Swing разработан компанией Sun Microsystems и содержит графические компоненты, такие как кнопки, поля ввода и таблицы. 
Swing относится к классу JFC (Java Foundation Classes) и поддерживает различные API, включая Java 2D, Accessibility-API, Drag & Drop-API и AWT.
