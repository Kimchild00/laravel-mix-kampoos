<template>
    <div class="container">
        <div class="row justify-content-center">
            <div class="col-md-8">
                <div class="card">
                    <div class="card-header text-center">Tambah buku</div>

                    <div class="card-body">
                        <form action="">
                            <div class="form-group">
                                <input type="text" name="name" id="" placeholder="Masukan Nama" class="form-control">
                            </div>
                            <div class="form-group">
                                <input type="text" name="title" id="" placeholder="Masukan Nama" class="form-control">
                            </div>
                            <div class="form-group">
                                <textarea name="description" class="form-control" id="" rows="5" holder="Description"></textarea>
                            </div>
                            <div class="form-group">
                                <router-link to="/" class="btn btn-warning">Kembali</router-link>
                                <button class="btn btn-success">Simpan</button>
                            </div>
                        </form>
                    </div>
                </div>
            </div>
        </div>
    </div>
</template>

<script>
</script>
