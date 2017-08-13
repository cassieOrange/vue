<template>
  <div class="new">
    <div class="btn">
      <span class="cancel">取消</span>
      <span class="keep">保存</span>
    </div>
    <textarea name="" id="" cols="30" rows="10" ></textarea>
    <div class="priority">
      <label class="pri-1"><input name="weight" type="radio" value="" checked/>很紧急-很重要</label>
      <label class="pri-2"><input name="weight" type="radio" value="" />很紧急-次重要</label>
      <label class="pri-3"><input name="weight" type="radio" value="" />次紧急-很重要</label>
      <label class="pri-4"><input name="weight" type="radio" value="" />次紧急-ci重要</label>
    </div>
    <div class="time">
      <img src="" alt="">
      <input type="datetime-local">
      <img src="" alt="">
      <input type="datetime-local">
    </div>
  </div>
</template>

<script>
  export default {
    name: 'hello',
    data () {
      return {
        msg: 'Welcome to Your Vue.js App'
      }
    }
  }
</script>

<style scoped>
  .btn{
    text-align: right;
    font-size: 14px;
    margin-bottom: 10px;
  }
  .btn .cancel{
    color: gray;
  }
  .btn .keep{
    color: deepskyblue;
    padding: 0 10px;
  }
  textarea{
    border:0;
    background-color:#FFEDE7;
    overflow: hidden;
    color: #666464;
    width: 100%;
    height: auto;
    padding: 8px;
  }
  .priority{
  }

  .smart-form .radio {
    margin-bottom: 4px;
    padding-left: 25px;
    line-height: 25px;
    color: #0c4757;
    cursor: pointer;
    font-size: 13px;

  }

  .smart-form .button.state-disabled, .smart-form .checkbox.state-disabled, .smart-form .input.state-disabled input, .smart-form .radio.state-disabled, .smart-form .select.state-disabled, .smart-form .textarea.state-disabled, .smart-form .toggle.state-disabled {
    cursor: default!important;
    opacity: .6!important;
  }
  .smart-form .state-disabled.checkbox input+i:after,
  .smart-form .state-disabled.checkbox input:checked+i,
  .smart-form .state-disabled.radio input+i:after,
  .smart-form .state-disabled.radio input:checked+i,
  .smart-form .state-disabled.toggle input:checked+i {
    border-color: #47A8C0 !important;
    color: #333!important;
  }
  /*add*/
  .smart-form .checkbox.checkbox-inline,
  .smart-form .radio.radio-inline{
    display: inline-block;
  }
  /*add*/
  .smart-form .checkbox input,
  .smart-form .radio input {
    position: absolute;
    left: -9999px;
  }

  .smart-form .checkbox i,
  .smart-form .radio i {
    position: absolute;
    top: 6px;
    left: 0;
    display: block;
    width: 15px;
    height: 15px;
    outline: 0;
    border-width: 1px;
    border-style: solid;
    background: #9cd9e8;
  }

  .smart-form .radio i {
    border-radius: 50%;
  }

  .smart-form .checkbox i,
  .smart-form .icon-append,
  .smart-form .icon-prepend,
  .smart-form .input input,
  .smart-form .radio i,
  .smart-form .select select,
  .smart-form .textarea textarea,
  .smart-form .toggle i {
    border-color: #47A8C0 ;
    transition: border-color .3s;
    -webkit-transition: border-color .3s;
  }

  .smart-form .checkbox input:checked+i,
  .smart-form .radio input:checked+i, .smart-form .toggle input:checked+i {
    border-color: #47A8C0 ;
  }

  .smart-form .checkbox input+i:after, .smart-form .radio input+i:after {
    position: absolute;
    opacity: 0;
    transition: opacity .1s;
    -webkit-transition: opacity .1s;
  }

  .smart-form .radio input+i:after {
    content: '';
    top: 3px;
    left: 3px;
    width: 9px;
    height: 9px;
    border-radius: 50%;
  }

  .smart-form .radio input+i:after {
    background-color: #47A8C0 ;
  }

  .smart-form .checkbox input:checked+i:after,
  .smart-form .radio input:checked+i:after {
    opacity: 1;
  }

  .smart-form .checkbox input+i:after {
    content: '\f00c';
    top: -3px;
    left: 1px;
    width: 15px;
    height: 15px;
    font: 400 16px/19px FontAwesome;
    text-align: center;
  }

</style>
