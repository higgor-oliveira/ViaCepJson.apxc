# ViaCepJson.apxc

public class ViaCepJson {
    @AuraEnabled public String cep;
    
    @AuraEnabled public String logradouro;
    
    @AuraEnabled public String complemento; /* ATRIBUTOS DO NOSSO RETORNO */
    @AuraEnabled public String bairro;
    @AuraEnabled public String localidade;
    @AuraEnabled public String uf; /* AURAENABLED PARA O LWC CONSIGA VER ESTES METODOS */
    @AuraEnabled public String unidade;
    @AuraEnabled public String ibge;
    @AuraEnabled public String gia;
     
    public ViaCepJson(){}
}



/* PARA EVITAR UTILIZAR MAPA, MONTA ESTA CLASSE DE OBJETO PARA O JSON SE DESEARILIZAR DE FORMA MAIS AGIL*/
