<template>
<div class="row pricing-table-two">
  <div class="col-lg-12">
    <div class="section-title text-center section-space--mb_60">
      <h2 class="font-weight--light mb-15">{{ $t('nodes.heading1') }}</h2>
      <p> {{ $t('nodes.desc') }} </p>
    </div>
  </div>
  <div class="col-md-6 col-lg-4 pricing-table pricing-table--popular wow move-up">
    <div class="pricing-table__inner">
      <div class="pricing-table__header">
        <div class="pricing-table__image">
          <img src="../assets/img/other/server1.svg" class="img-fluid" alt="Service Node">
        </div>
        <h5 class="pricing-table__title">Service Node</h5>
        <div class="pricing-table__price-wrap">
          <h6 class="price">5000 ETHO</h6>
        </div>
      </div>
      <p>{{ $t('nodes.sn') }}</p>
      <h5 class="pricing-table__title">Service Node {{ $t('nodes.requirements') }}:</h5>
      <div class="pricing-table__body">
        <ul class="pricing-table__list text-left">
          <li>20 GB {{ $t('nodes.storage') }}</li>
          <li>1 GB {{ $t('nodes.ram') }}</li>
          <li> {{ $t('nodes.ip') }}</li>
        </ul>
      </div>
    </div>
  </div>
  <div class="col-md-6 col-lg-4 pricing-table pricing-table--popular wow move-up">
    <div class="pricing-table__inner">
      <div class="pricing-table__header">
        <div class="pricing-table__image">
          <img src="../assets/img/other/server2.svg" class="img-fluid" alt="Pricing Thumb">
        </div>
        <h5 class="pricing-table__title">Master Node</h5>
        <div class="pricing-table__price-wrap">
          <h6 class="price">15000 ETHO</h6>
        </div>
      </div>
      <p>{{ $t('nodes.mn') }}</p>
      <h5 class="pricing-table__title">Master Node {{ $t('nodes.requirements') }}:</h5>
      <div class="pricing-table__body">
        <ul class="pricing-table__list text-left">
          <li>40 GB {{ $t('nodes.storage') }}</li>
          <li>2 GB {{ $t('nodes.ram') }}</li>
          <li>{{ $t('nodes.ip') }}</li>
        </ul>
      </div>
    </div>
  </div>
  <div class="col-md-6 col-lg-4 pricing-table pricing-table--popular wow move-up">
    <div class="pricing-table__inner">
      <div class="pricing-table__header">
        <div class="pricing-table__image">
          <img src="../assets/img/other/server3.svg" class="img-fluid" alt="Pricing Thumb">
        </div>
        <h5 class="pricing-table__title">Gateway Node</h5>
        <div class="pricing-table__price-wrap">
          <h6 class="price" id="sn">30000 ETHO</h6>
        </div>
      </div>
      <p>{{ $t('nodes.gn') }}</p>
      <h5 class="pricing-table__title">Gateway Node {{ $t('nodes.requirements') }}:</h5>
      <div class="pricing-table__body">
        <ul class="pricing-table__list text-left">
          <li>80 GB {{ $t('nodes.storage') }}</li>
          <li>4 GB {{ $t('nodes.ram') }}</li>
          <li>{{ $t('nodes.ip') }}</li>
        </ul>
      </div>
    </div>
  </div>
</div>
</template>

<script>
export default {
  name: 'pricingTwo',
  data() {
    return {}
  },
}
</script>
