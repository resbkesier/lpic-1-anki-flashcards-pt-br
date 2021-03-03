Em um sistema que utilza BIOS qual é a ordem de boot?

---

Bios > MBR > Bootloader(GRUB) > Kernel > Init

===

Em qual arquivo ficam os sinais de interrupção do sistema (IRQ)?

---

/proc/interrupts

===

Onde o linux guarda os endereços de IO?

---

/proc/ioports

===

Onde o linux guarda os acessos diretos à memoria (DMA)?

---

/proc/dma

===

Qual comando serve para ver o que está conectado no barramento pci?

---

lspci

===

Qual o comando que serve para ver o que está conectado no barramento usb?

---

lsusb

===

Como ver detalhes do barramento pci?

---

lspci -s id_barramento -v

===

Como ver detalhes do barramento usb?

---

lsusb -s bus:device -v

===

Quais diretorios não podem estar em uma partição diferente do /?

---



===

Qual é o arquivo que guarda informaçoes sobre a cpu da maquina?

---

/proc/cpuinfo

===

Qual arquivo guarda os parâmetros passados para o kernel no momento de boot?

---

/proc/cmdline

===

Qual arquivo guarda informações sobre a memoria do computador?

---

/proc/meninfo

===

Qual é o arquivo que guarda informações sobre os tipos de filesystems suportados pelo kernel?

---

/proc/filesystems

===

Qual é o arquivo que que mostra os  mostra o status dos filesystems montados?

---

/proc/mounts

===

Qual é o tipo de filesystem que é usado para gerar algo dinamicamente?

---

tmpfs

===

Qual é o sinal responsavél pelo deligamento do sistema linux?

---

acpid

===

Se eu apontar um hard link para um arquivo em outra partição, qual será o resultado?

---

Vazia

===

Cite duas ferramentas usadas para poder rodar processos em outras sessões?

---

- tmux
- screen

===

Cite 3 formas de salvar e sair no editor de texto vim.

---

- :x
- :wq
- ZZ

===

Qual comando me mostra os modulos carregados?

---

lsmod

===

Qual comando é passado para remover modulos carregados?

---

- modprob -r module_name
- rmmod module_name

===

Em qual diretorio fica as regras que bloqueia o carregamento dos modulos de sistema?

---

/etc/modprobe.d

===

Qual é a ordem do processo de boot na bios?

---



===

Em qual lugar fica as configurações de runlevel padrão em um sistema init?

---

/etc/inittab

===

Em um sistema sysV  qual é o runlevel de single user?

---



===

Quais comandos eu uso para alterar o runlevel de uma máquina que usa um sistema sisV?

---

init, telinit

===

Em um sistem sysV, qual comando comando e parametro são usados para recarregar a configuração do init?

---

telinit q

===

Onde fica os arquivos de units do systemd?

---

/lib/systemd/system

===

Em um sistema que utiliza o systemctl qual parametro é usado para mudar de runlevel?

---

systemctl isolete

===

Qual comando eu verifico o status de um serviço no systemd?

---

systemctl status service_name.servce

===

Qual diretorio guarda informações sobre as unidades do systemd?

---

/lib/systemd/system

===

Cite três formas de reiniciar um sistema linux:

---

- init 6
- shutdown -r
- reboot

===

Qual comando me permite mandar uma mensagem para todos os usuarios logados no sistema?

---

wall

===

Em um sistema que utiliza bios, qual local do disco fica gravado as informações do Boot loader (grub)?

---

nos primeiros 446 bytes do disco

===

Quais comandos podem ser utilizados para ver o processo de boot?

---

- dmesg
- journalctl -b

===

Em uma máquina que utliza BIOS qual é o estágio de boot responsável por carregar o bootloader (grub)?

---

MBR

===

Em um sistema UEFI qual é o processo de boot?

---

UEFI > Bootloader(grub) > Kenel > Init

===

Qual comando que me permite verificar a versão do kernel?

---

uname -r

===

Quais comandos podem ser utilizados para atualizar o arquivo de configuração utilizado durante o processo de boot pelo GRUB 2?

---



===

Em qual diretório é por padrão montada a partição ESP (EFI System Partition)?

---

/boot/efi

===

Ao executar o comando `nice -10 service`, qual atributo e valor é definido ao processo?

---

 

===

Um sistema que possui as seguintes partições:

```
/dev/sda1
/dev/sda2
/dev/sda3
/dev/sda5
/dev/sda6
```

Quantas partições são do tipo lógica?
Existe alguma partição do tipo extendida?

---



===

Qual variável embutida no Bash retorna o valor do PID do shell atual?

---

$$

===

Qual variável de ambiente contém o nome do arquivo utilizado para armazenar os últimos comandos utilizados por um usuário?

---



===

Em quais diretórios de um sistema Linux estão localizados arquivos binários que só podem ser executados pelo usuário root?

---



===

Quais são as partições virtuais?

---



===

qual processo é responsável por referenciar os dispositivos conectados?

---



===

Qual serviço e responsavel por lidar com as questões de energia?

---



===

Informe pelo menos 3 comandos diferentes para reiniciar uma máquina Linux.

---



===

Em um sistema que utilza UEFI qual é a ordem de boot?

---



===


Em um sistema que utiliza UEFI one fica a partição ESP?

---



===