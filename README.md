<?php  require_once (" ../../conexao/conexao.php "); ?>

<!doctype html >
<html> _ _
    < cabeça >
        < meta  charset =" UTF-8 " >
        < meta  name =" janela de visualização " conteúdo =" largura=largura do dispositivo, escala inicial=1,0 " >
        < title > Curso PHP Integração com MySQL </ title >
        
        <!-- estilo -->
        < link  href =" _css/estilo.css " rel =" folha de estilo " >
    </ cabeça >

    < corpo >
        <?php  include_once (" ../_incluir/topo.php "); ?>
        <?php  include_once (" ../_incluir/funcoes.php "); ?>
        
        <principal> _ _  
            
        </principal> _ _

        <?php  include_once (" ../_incluir/rodape.php "); ?> 
    </ corpo >
</html> _ _

<?php
    // Fechar conexão
    mysqli_close( $ conecta );
?>
