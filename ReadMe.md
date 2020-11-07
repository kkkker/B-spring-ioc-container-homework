> @Componment是在标注在类上的注解，而@Bean是标注在方法上的注解。
> 当使用已经写好的但是没有@Componment标注的类的时候，就只能通过@Bean的方式，将对象放入Ioc容器中。