# WssRest.pdf
#Explique quais são as seis regras de uma API REST.

As seis regras de uma API REST são:

    Cliente-Servidor: A API REST é baseada em um arquitetura cliente-servidor, onde o cliente envia uma requisição ao servidor e o servidor retorna uma resposta. Isso permite que a aplicação seja escalável e evita problemas de estado.

    Statelessness: Uma API REST é stateless, ou seja, não mantém estado entre as requisições. Cada requisição deve conter toda a informação necessária para ser processada pelo servidor.

    Cacheabilidade: Uma API REST deve ser cacheável para melhorar o desempenho. Isso significa que o cliente pode armazenar a resposta em cache e usá-la novamente sem ter que fazer uma nova requisição ao servidor.

    Intermediação: A API REST é intermediada, o que significa que pode haver vários intermediários entre o cliente e o servidor, como firewalls, proxies, etc. Cada intermediário pode adicionar cabeçalhos à requisição ou a resposta, mas não deve mudar a informação original.

    Codificação de Representação: A API REST usa diversos formatos de representação, como JSON ou XML, para representar os recursos. O cliente e o servidor concordam em um formato específico usando o cabeçalho "Content-Type".

    Verbos HTTP: A API REST usa os verbos HTTP (GET, POST, PUT, DELETE, etc.) para indicar a ação a ser executada na requisição. Por exemplo, o verbo GET é usado para recuperar um recurso, enquanto o verbo DELETE é usado para excluir um recurso.
