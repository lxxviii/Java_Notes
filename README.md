## Java_Notes

### DAO (Data Access Object)          : Veri Tabanı üzerinde yapılacak işlemleri yüklenen sınıflardır. Database işlemleri tekrar tekrar kullanımı sağlanır. (Code Reuse)

### DTO (Data Transfer Object)        : DB-JVM veya JVM-JVM arasında Sadece Veri Aktarımı için kullanılır.
  1. Depolama Dışında Herhangi bir yükümlülüğü yoktur.
  2. Setter / Getter kullanımına gerek yoktur. Tüm veriler "public" olarak tutulabilir.
     
### JavaBean                          : Veri Tutma amaçlı olarak kullanılır. Bir objeinin JavaBean olarak sayılabilmesi için 
  1. Serialize olmalı       // Text Dosyasında depil DB'de tutulduğundan Bean/POJO daha yaygındır.
  2. Parametresi Yapıcı Metodu olmalı (+No Parameter Constructor)
  3. Public setter / getter motodlarına sahip olmalı
     
### POJO/Bean(Plain Old Java Object)  : Bu obje de veri depolamak için kullanılır. Örneğin Kullanıcı Bilgilerinin Tutulacağı Objeye UserBean denilebilir.

### VO (Value Object)                 : java.lang.Integer 
JavaBeans API
The JavaBeans functionality is provided by a set of classes and interfaces in the java.beans package.

Interface	Description
AppletInitializer	Methods in this interface are used to initialize Beans that are also applets.
BeanInfo	This interface allows the designer to specify information about the events, methods and properties of a Bean.
Customizer	This interface allows the designer to provide a graphical user interface through which a bean may be configured.
DesignMode	Methods in this interface determine if a bean is executing in design mode.
ExceptionListener	A method in this interface is invoked when an exception has occurred.
PropertyChangeListener	A method in this interface is invoked when a bound property is changed.
PropertyEditor	Objects that implement this interface allow the designer to change and display property values.
VetoableChangeListener	A method in this interface is invoked when a Constrained property is changed.
Visibility	Methods in this interface allow a bean to execute in environments where the GUI is not available.
