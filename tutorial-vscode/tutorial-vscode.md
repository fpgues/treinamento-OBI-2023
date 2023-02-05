# **Tutorial para preparação do ambiente de desenvolvimento**

Nesse tutorial vamos aprender. 
1) Como instalar o Visual Studio Code.
2) Fazer a instalação do compilador para C++.
3) Executar o nosso primeiro programa.

# **1) Instalando o editor de código Visual Studio Code.**

Visual Studio Code é um editor de código-fonte (gratuito) desenvolvido pela Microsoft para Windows, Linux e macOS, tendo suporte para várias linguagens de programação.

> O tutorial a seguir foi realizado no Sistema Operacional Windows 10.

## **Instalação**

1) Acesse o site oficial do Visual Studio Code: https://code.visualstudio.com/


2) Clique no botão "**Download**" para baixar o instalador.

<div align="center">

![passo01](https://user-images.githubusercontent.com/114113408/216842285-f1b7377e-7ddf-44af-a797-17acb43acf9a.PNG)

</div>

3) Escolha a pasta de destino e clique em "**Salvar**". Após o download finalizar, abra o arquivo.

4) Execute o arquivo baixado em modo **ADMINISTRADOR** e siga as instruções.

<div align="center">

![passo02](https://user-images.githubusercontent.com/114113408/216842288-25b813fd-40ac-4b1f-889a-17fb57605901.PNG)

</div>

<div align="center">

![passo03](https://user-images.githubusercontent.com/114113408/216842291-77c97096-49d2-495a-9df4-15011899630a.PNG)

</div>

<div align="center">

![passo04](https://user-images.githubusercontent.com/114113408/216842292-e75d0045-361d-489f-9ebe-3d297dfeba77.PNG)

</div>

<div align="center">

![passo05](https://user-images.githubusercontent.com/114113408/216842293-9f578d1a-a780-45aa-a3a6-b7b81fda156f.PNG)

</div>

<div align="center">

![passo06](https://user-images.githubusercontent.com/114113408/216842295-83207017-4a20-4c4f-94df-2a042f07f394.PNG)

</div>

<div align="center">

![passo07](https://user-images.githubusercontent.com/114113408/216842296-f90deeb2-cfd8-4a12-bfd4-df1c854b708b.PNG)

</div>

5) Após a instalação, abra o programa.

-------
# **2) Instalando o compilador de C++ MinGW.**

No próprio site do Visual Studio Code tem o link para o compilador. 


1) Acesse: https://code.visualstudio.com/docs/cpp/config-mingw

2) Descendo um pouco a página você encontra a opção de baixar o instalador. (*link to the installer*).


<div align="center">

![compilador01](https://user-images.githubusercontent.com/114113408/216842421-1a94c4cd-1724-4c4f-8a60-63d8b9591cb1.PNG)

</div>

3) **OBS:** Após finalizar o download, execute o instalador em modo **ADMINISTRADOR**.

<div align="center">

![compilador02](https://user-images.githubusercontent.com/114113408/216842423-85033273-8291-41fd-a320-348c28b2def2.PNG)

</div>

> **Atenção: Não mude o local da pasta padrão.**

<div align="center">

![compilador03](https://user-images.githubusercontent.com/114113408/216842424-450502e1-5129-498f-b8ba-162a09b7ba32.PNG)

</div>

<div align="center">

![compilador04](https://user-images.githubusercontent.com/114113408/216842427-c8406dc9-a40c-4b44-9adb-f3facbca0e78.PNG)
</div>

<div align="center">

![compilador05](https://user-images.githubusercontent.com/114113408/216842429-f4347513-f992-4b0f-bb2b-6eb32a174b72.PNG)

</div>

**Digite o comando no MSYS2.**

- ``` pacman -S --needed base-devel mingw-w64-x86_64-toolchain ```

<div align="center">

![compilador06](https://user-images.githubusercontent.com/114113408/216842430-5ee94d55-4920-4cbe-8045-2e9be429cbb5.PNG)

</div>

4) Aperte ENTER.

<div align="center">
    
![compilador07](https://user-images.githubusercontent.com/114113408/216849717-77696638-b807-41f3-b426-b97801f4fa6d.PNG)

</div>

5) Aperte ENTER ou Y+ENTER para baixar os arquivos.

<div align="center">

![compilador08](https://user-images.githubusercontent.com/114113408/216842432-b7949e6a-247b-4ea1-b379-ea9066953e43.PNG)

</div>


### Agora vamos configurar as variáveis de ambiente.

6) Aperte a tecla WINDOWS e digite 'configurações', digite **variáveis de ambiente** e clique em **Editar as variáveis de ambiente para sua conta**.

<div align="center">

![compilador10](https://user-images.githubusercontent.com/114113408/216843204-49dd5f05-c616-4d0d-94a9-dfd22039133f.PNG)

</div>

<div align="center">

![compilador11](https://user-images.githubusercontent.com/114113408/216843083-8edf384e-334d-4bcd-9c61-8f80c07405db.PNG)

</div>

<div align="center">

![compilador12](https://user-images.githubusercontent.com/114113408/216843084-be81bc45-6123-4650-9547-e45b02342e3b.PNG)

</div>

    OBS: Atenção ao caminho que você irá adicionar, ele precisa ser exatamente onde você instalou. 

7) A pasta padrão é essa: **C:\msys64\mingw64\bin**

<div align="center">

![compilador13](https://user-images.githubusercontent.com/114113408/216843085-2d1b7977-4cbf-4da9-9ec8-b04de839ee83.PNG)

</div>

Verificando se tudo ocorreu bem, digite no **CMD**.

- ```g++ --version```

<div align="center">
    
![compilador-finall](https://user-images.githubusercontent.com/114113408/216849855-f482d32f-1e15-4c49-9a43-9c76e03d6d91.PNG)

</div>

-------

# Criando o nosso primeiro programa.

1) Crie uma pasta no seu computador. Neste tutorial uma pasta chamada "workspace" foi criada na área de trabalho.

2) Utilizando o programa que instalamos, o Visual Studio Code.

<div align="center">

![visual01](https://user-images.githubusercontent.com/114113408/216845624-0dc1aca8-e3b3-4ec6-b8fb-f11650af3c4d.PNG)

</div>

3) Selecione a pasta indicada.

<div align="center">

![visual02](https://user-images.githubusercontent.com/114113408/216845627-76e2ea97-48f9-4797-b2c8-165fbc6f8e6f.PNG)

</div>

4) Crie o arquivo *helloworld.cpp*

<div align="center">

![visual03](https://user-images.githubusercontent.com/114113408/216845628-62cd1d03-ee9a-42d4-8490-e3b2a585bd19.PNG)

</div>

5) Observe o arquivo criado e em seguida escreva o seu primeiro programa.
Obs: Não esqueça da extensão no final do arquivo ".cpp"

```
#include <iostream>
using namespace std;

int main()
{
    cout << "Hello World! " << endl;
    return 0;
} 
```
<div align="center">

![visual05](https://user-images.githubusercontent.com/114113408/216845629-6e953118-1984-47f8-a62c-66e099f30221.PNG)

</div>

Salve o arquivo (Ctrl+S) e escreva no terminal do VS Code:

```g++ helloworld.cpp -o a``` 

Depois 

```.\a.exe```

<div align="center">
    
![visual077](https://user-images.githubusercontent.com/114113408/216851151-4a3e7ffc-95ee-4159-a970-8a0be504e9bd.PNG)

</div>

-----------

# Conclusão

O que aprendemos nesse tutorial?

1) Como instalar o editor de código VSCode.
2) Baixar e configurar o compilador.
3) Compilar e executar um programa. 

Agora o seu ambiente de desenvolvimento está pronto! Você já pode mergulhar nos estudos.

Até mais e esperamos que seja útil.
