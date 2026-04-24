FROM maven
WORKDIR /opt/server
COPY src/* .
COPY pom.xml .
CMD ["sleep", "1000"]
# RUN mvn clean package
# RUN mv /opt/server/target/shipping-*.jar /opt/server/shipping.jar
# ENV CART_ENDPOINT=cart:8080 \
#     DB_HOST=mysql
# CMD ["java", "-jar", "shipping.jar"]