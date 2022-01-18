<script>
export default {
    middleware: [
        function({ redirect }) {
            redirect('/static/cardapio_primavera.pdf');
        },
    ],
};
</script>