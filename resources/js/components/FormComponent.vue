<template>
    <div>
        <div class="card-body">
            <div class="container-fluid">
                <div class="row">
                    <div class="col align-self-center justify-content-center mx-auto">
                        <img src="https://locatelcolombia.vteximg.com.br/arquivos/logo.png" class="img-fluid mx-auto d-block w-50" alt="Responsive image">
                    </div>
                </div>
                <div class="card card-success">
                    <div class="card-header">
                        <h3 class="card-title">Gestión De Clientes</h3>
                    </div>
                    <div class="card-body">
                        <div class="row">
                            <div class="col-md-4">
                                <label>Tipo de identificación</label>
                                <select class="form-control form-control-lg select2">
                                    <option>Cédula de ciudadania</option>
                                    <option>Cédula de extranjería</option>
                                    <option>Tarjeta de extranjería</option>
                                    <option>Pasaporte</option>
                                    <option>Documento de indentificación extranjero</option>
                                    <option>Registro civil de nacimiento</option>
                                    <option>Tarjeta de identidad</option>
                                </select>
                            </div>
                            <div class="col-md-4">
                                <label>Identificación</label>
                                <input class="form-control form-control-lg" type="number" placeholder="Número De Identificacion">
                            </div>

                            <div class="col-md-4">
                                <label>Tipo de persona</label>
                                <input class="form-control form-control-lg" readonly type="text"
                                       value="persona natural">
                            </div>
                        </div>
                        <div class="row mt-3">
                            <div class="col-md-3">
                                <label>Nombre</label>
                                <input class="form-control form-control-lg" type="text" placeholder="Nombre">
                            </div>
                            <div class="col-md-3">
                                <label>Apellidos</label>
                                <input class="form-control form-control-lg" type="text" placeholder="Apellidos">
                            </div>

                            <div class="col-md-3">
                                <label>Teléfono</label>
                                <input class="form-control form-control-lg" type="number" placeholder="Teléfono">
                            </div>
                            <div class="col-md-3">
                                <label>Email</label>
                                <input class="form-control form-control-lg" type="number" placeholder="Email">
                            </div>
                        </div>
                        <div class="row mt-3">
                            <div class="col-md-3">
                                <label>País</label>
                                <select class="form-control form-control-lg select2">
                                    <option>Colombia</option>
                                    <option>Argentina</option>
                                    <option>Brazil</option>
                                </select>
                            </div>
                            <div class="col-md-3">
                                <label>Departamento</label>
                                <select class="form-control form-control-lg select2">
                                    <option>Cundinamarca</option>
                                    <option>Bogota</option>
                                    <option>Atlántico</option>
                                    <option>Antioquía</option>
                                </select>
                            </div>
                            <div class="col-md-3">
                                <label>Ciudad</label>
                                <select class="form-control form-control-lg select2">
                                    <option>Bogotá</option>
                                    <option>Barranquilla</option>
                                    <option>Medellín</option>
                                </select>
                            </div>
                            <div class="col-md-3">
                                <label>Dirección</label>
                                <input class="form-control form-control-lg" type="text" placeholder="Dirección">
                            </div>
                        </div>
                        <div class="col-md-6 mt-3">
                            <div class="form-check">
                                <input class="form-check-input" type="checkbox" value="">
                                <label class="form-check-label">
                                    Acepta las políticas de tratamiento de datos
                                </label>
                            </div>
                            <div class="form-check">
                                <input class="form-check-input" type="checkbox" value="">
                                <label class="form-check-label">
                                    Acepta tratamiento de datos por habeas data
                                </label>
                            </div>
                        </div>
                        <div class="row-cols-6 mt-3">
                            <div class="mx-auto">
                                <button type="button" class="btn btn-success btn-lg">Registar</button>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </div>
</template>
<script>
export default {
    name: "FormComponent"
}
</script>
<style scoped>
</style>
