<script>
    import Header from "./Header";
    import axios from "axios";
    export default {
        name: "SignUp",
        components: {
            Header
        },
        data() {
            return {
                model: {
                    name: "",
                    email: "",
                    password: "",
                    c_password: "",
                    company_name: ""
                },
                loading: "",
                status: ""
            };
        }
    }
</script>