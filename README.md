# DIO - Criando Máquinas Virtuais na Azure
 Criação de máquinas Virtuais na Azure


## 🔎 Contratos de Nível de Serviço (SLA) para Serviços Online	

>Os SLAs (Contratos de Nível de Serviço) descrevem os compromissos da Microsoft para tempo de atividade e conectividade para o Microsoft Online Services. As edições atuais e arquivadas do SLA estão disponíveis para download e abrangem o Azure, o Dynamics 365, o Office 365 e o Intune.

Exemplos de SLAs utilizados:
![AZ02-10](https://github.com/user-attachments/assets/4628e281-2526-4795-85c5-9f41fe547fa2)

<sub>Fonte: <https://www.microsoft.com/licensing/docs/view/Service-Level-Agreements-SLA-for-Online-Services?lang=1></sub>


## Criação da Máquina Virtual no Azure

Abra o portal do [`Azure`](https://portal.azure.com), clique em **Todos os serviços**, **Computação** e **Máquinas Virtuais**.

![AZ02-01](https://github.com/user-attachments/assets/39465027-4fb7-48c0-a0ae-2f731d994d2e)

Na página **Máquinas Virtuais**, clique em **+ Criar** e após clique na opção **Máquina Virtual do Azure**.

![AZ02-02](https://github.com/user-attachments/assets/6f46cc8e-a9f2-4a1c-a786-41cb68e3c07e)

Na tela que abrir será necessário informar uma **Assinatura** e um **Grupo de recursos**, além dos **Detalhes da instância**.

![AZ02-03](https://github.com/user-attachments/assets/ad37715e-7f40-4510-a61c-8644c9542524)

![AZ02-04](https://github.com/user-attachments/assets/92c101da-2b83-4f54-9562-9105a5f78b72)

No grupo de campos **Detalhes da instância** os que mais se destacam são os listados abaixo:

- **Opções de disponibilidade** cuja função se encontra destacada na imagem abaixo:

![AZ02-05](https://github.com/user-attachments/assets/78bcbec7-2f6f-4a57-a5ee-07ac3da518cf)

![AZ02-09](https://github.com/user-attachments/assets/016fd6b7-ad7b-493f-bf5e-6a3b0d7650c5)

- **Zona de disponibilidade** cuja função se encontra destacada na imagem abaixo, e permite que sejam selecionadas várias zonas de disponibilidade para a máquina virtual a ser criada:

![AZ02-06](https://github.com/user-attachments/assets/bb38dc1f-1a06-4687-8014-9f543807b531)

![AZ02-07](https://github.com/user-attachments/assets/3e739ef3-21ed-4475-896f-a789b4d2398c)

![AZ02-08](https://github.com/user-attachments/assets/1a346812-d1df-483a-8df1-6421db5132a9)

Após ter preenchido todas as informações necessárias para a criação da Máquina Virtual, basta clicar na opção **Revisar + criar**, e confirmar a criação.

![AZ02-11](https://github.com/user-attachments/assets/636597f4-8ef6-470d-a329-b8a13a17af3a)


## Links utilizados

- https://www.microsoft.com/licensing/docs/view/Service-Level-Agreements-SLA-for-Online-Services?lang=1

- https://portal.azure.com/#browse/Microsoft.Compute%2FVirtualMachines
