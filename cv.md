## Ivan Druzhinin

### Contacts
**e-mail: mrdruzhinin.ia@gmail.com**

### Summary
I work as a backend developer and want to improve my frontend knowledge to interact more consciously with the frontend developers on my team. Maybe someday I will retrain as a full-stack developer

### Skills
Now it is Java, but before that I had quite a lot of experience in C/C++ embedded development

### Code samples
```Java
@Configuration
public class LifeconnectAnalyzerConfigJMS {
    @Bean
    public MessageConverter jacksonJmsMessageConverter(){
        MappingJackson2MessageConverter converter =  
                new MappingJackson2MessageConverter();
        
        converter.setTargetType(MessageType.TEXT);        
        converter.setTypeIdPropertyName("_class_");
        return converter;
    }
    
    @Bean
    public JmsListenerContainerFactory<?> jmsFactory(ConnectionFactory connectionFactory,
            DefaultJmsListenerContainerFactoryConfigurer configurer){
        DefaultJmsListenerContainerFactory factory = 
                new DefaultJmsListenerContainerFactory();
        configurer.configure(factory, connectionFactory);
        return factory;
    }
}

```
### Work experience
Several years as a developer of embedded software and digital devices, several years as a Java backend developer

### Education
Dubna State University

### English
Upper-Intermediate