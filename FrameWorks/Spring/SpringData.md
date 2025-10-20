# Db on Spring

- Fetching strategies

- lazy is the default fetching strategies
- eager

```
@Entity
@Table(name = "Customer")
public class Customer {
  @ElementCollection (fetch = FetchType.EAGER)
  @CollectionTable(name = "customer_contact_number",
        joinColumns = @JoinColumn(name = "customer_id"))
  @Column(name = "mobile_number", nullable = false)
  private Set<Integer> phoneNumbers;
}
```

Application properties config

```

spring.jpa.hibernate.ddl-auto=update


#MySQL
spring.datasource.url=jdbc:mysql://localhost:3306/dbname
spring.datasource.username=root
spring.datasource.password=admin

```
