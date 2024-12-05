<template>
    <blockquote>
        <h3>Informações</h3>
        <ul>
            <li><strong>Horário de funcionamento:</strong> Segunda a Sexta, das 9h às 18h.</li>
            <li><strong>Endereço:</strong> Rua Exemplo, 123 - Centro, Cidade, País.</li>
            <li><strong>Contato:</strong> (99) 9999-9999 | exemplo@email.com</li>
            <li><strong>Política de Privacidade:</strong> Valorizamos sua privacidade e segurança. Consulte nossa
                política no rodapé.</li>
        </ul>
    </blockquote>
</template>

<script>
export default {
    name: 'PagInfo',
};
</script>

<style>
blockquote {

    border: 2px solid #2c3e50;
    text-align: center;

}

h3 {
    text-align: center;
    margin-bottom: 15px;
    color: #2c3e50;
}

p {
    margin-bottom: 15px;
    color: #34495e;
    font-size: 18px;
}

ul {
    list-style-type: none;
    padding: 0;
    margin: 0;
}

li {
    margin-bottom: 10px;
    font-size: 16px;
    color: #555;
}

li strong {
    color: #333;
}
</style>