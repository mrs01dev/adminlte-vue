<template>
  <Card>
    <template slot="header">
      <CardHeader title="Recently Added Products">
        <template slot="tools">
          <button type="button" class="btn btn-tool" data-card-widget="collapse">
            <i class="fas fa-minus"></i>
          </button>
          <button type="button" class="btn btn-tool" data-card-widget="remove">
            <i class="fas fa-times"></i>
          </button>
        </template>
      </CardHeader>
    </template>
    <template slot="body">
      <card-body class="p-0">
        <ul class="products-list product-list-in-card pl-2 pr-2">
          <li class="item">
            <div class="product-img">
              <img src="/dist/img/default-150x150.png" alt="Product Image" class="img-size-50">
            </div>
            <div class="product-info">
              <a href="javascript:void(0)" class="product-title">Samsung TV
                <span class="badge badge-warning float-right">$1800</span></a>
              <span class="product-description">
                        Samsung 32" 1080p 60Hz LED Smart HDTV.
                      </span>
            </div>
          </li>
          <!-- /.item -->
          <li class="item">
            <div class="product-img">
              <img src="/dist/img/default-150x150.png" alt="Product Image" class="img-size-50">
            </div>
            <div class="product-info">
              <a href="javascript:void(0)" class="product-title">Bicycle
                <span class="badge badge-info float-right">$700</span></a>
              <span class="product-description">
                        26" Mongoose Dolomite Men's 7-speed, Navy Blue.
                      </span>
            </div>
          </li>
          <!-- /.item -->
          <li class="item">
            <div class="product-img">
              <img src="/dist/img/default-150x150.png" alt="Product Image" class="img-size-50">
            </div>
            <div class="product-info">
              <a href="javascript:void(0)" class="product-title">
                Xbox One <span class="badge badge-danger float-right">
                        $350
                      </span>
              </a>
              <span class="product-description">
                        Xbox One Console Bundle with Halo Master Chief Collection.
                      </span>
            </div>
          </li>
          <!-- /.item -->
          <li class="item">
            <div class="product-img">
              <img src="/dist/img/default-150x150.png" alt="Product Image" class="img-size-50">
            </div>
            <div class="product-info">
              <a href="javascript:void(0)" class="product-title">PlayStation 4
                <span class="badge badge-success float-right">$399</span></a>
              <span class="product-description">
                        PlayStation 4 500GB Console (PS4)
                      </span>
            </div>
          </li>
          <!-- /.item -->
        </ul>
      </card-body>
    </template>
    <template slot="footer">
      <card-footer class="text-center">
        <a href="javascript:void(0)" class="uppercase">View All Products</a>
      </card-footer>
    </template>
  </Card>
</template>
<script>
import Card from '@/components/Widget/Card/ACard'
import CardHeader from '@/components/Widget/Card/ACardHeader'
import CardBody from '@/components/Widget/Card/ACardBody'
import CardFooter from '@/components/Widget/Card/ACardFooter'

export default {
  name: 'AProductRecentAdded',
  components: {
    Card,
    CardHeader,
    CardBody,
    CardFooter
  },
  data () {
    return {}
  },
  props: {}
}
</script>
