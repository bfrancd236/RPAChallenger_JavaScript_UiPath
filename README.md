![enter image description here](https://www.uipath.com/hubfs/img/og-image-orange.png)
# [RPA Challenger] UiPath com JavaScript
## 💻 Projeto
Challenger de Robotic Process Automation afim de desenvolver habilidades com a ferramenta UiPath enfrentando dificuldades, mais dados sobre o challenger: [Clique aqui.](https://rpachallenge.com/)

### 📄 Solução aplicada para obter menos tempo de execução
Afim de utilizar um menor tempo para esse challenger foi utilizado javaScript e não funções nativas da aplicação, presando pela velocidade de execução.

    function (e, valor){
    document.querySelector("[ng-reflect-name='labelFirstName']").value = valor.split("-")[0];
    document.querySelector("[ng-reflect-name='labelLastName']").value = valor.split("-")[1];
    document.querySelector("[ng-reflect-name='labelCompanyName']").value = valor.split("-")[2];
    document.querySelector("[ng-reflect-name='labelRole']").value = valor.split("-")[3];
    document.querySelector("[ng-reflect-name='labelAddress']").value = valor.split("-")[4];
    document.querySelector("[ng-reflect-name='labelEmail']").value = valor.split("-")[5];
    document.querySelector("[ng-reflect-name='labelPhone']").value = valor.split("-")[6];
    document.querySelector("[value='Submit']").click();
    }

### 🚀 Resultado final
![enter image description here](https://i.imgur.com/1DjEbM3.png)
