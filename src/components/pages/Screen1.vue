<template>
  <NucGridPage v-bind:gap="{'col':0,'row':0}" v-bind:rows="[1]"
    v-bind:schema="{'r0-c0':{'col':0,'row':0,'showIn':['xs','sm','md','lg'],'colSpan':1,'rowSpan':1}}"
    v-bind:columns="[1]" overflow="auto" v-bind:designMode="false" v-bind:minNsLimit="0"
    v-bind:style="{'background':'#FFFFFF','paddingTop':'0px','paddingLeft':'0px','paddingRight':'0px','paddingBottom':'0px'}">
    <NucGridCell v-bind:wrap="true" v-bind:reverse="false" overflow="hidden" direction="column"
      v-bind:showInDevice="['xs','sm','md','lg']" verticalAlignment="top" horizontalAlignment="left"
      id="5901b62d-82b6-478f-b7e4-f4557ef92b07" v-bind:col="0" v-bind:row="0" v-bind:colSpan="1" v-bind:rowSpan="1"
      v-bind:marginTop="0" v-bind:marginLeft="0" v-bind:marginRight="0" v-bind:marginBottom="0"
      v-bind:style="{'height':'auto','background':'transparent','paddingTop':'0px','borderColor':'','borderStyle':'solid','borderWidth':'0px','paddingLeft':'0px','borderRadius':'0px','paddingRight':'0px','paddingBottom':'0px','borderTopWidth':'0px','borderLeftWidth':'0px','borderRightWidth':'0px','borderBottomWidth':'0px','borderTopLeftRadius':'1px','borderTopRightRadius':'1px','borderBottomLeftRadius':'1px','borderBottomRightRadius':'1px'}"
      slot="r0-c0" area="r0-c0">
      <WCalendar v-bind:fade="false" text="Text Content 1" theme="theme--light01" ImgAlt="Blank Image 1"
        v-bind:noWrap="false" caption="Carousel 1" v-bind:noTouch="false"
        imageUrl="https://picsum.photos/500/250/?image=1082" v-bind:interval="5000" v-bind:isEnabled="true"
        background="" blankColor="#ababab" v-bind:indicators="false" secondText="Text Content 2"
        v-bind:noAnimation="false" ncTypography="body2" v-bind:noHoverPause="false" secondImgAlt="Blank Image 2"
        secondCaption="Carousel 2"
        v-bind:nucalDataModel="{'type':'NSW','isList':false,'dynamic':false,'structure':[{'type':'string','propName':'imageUrl','displayName':'ImageUrl'},{'type':'string','propName':'secondImageUrl','displayName':'SecondImageUrl'}]}"
        secondImageUrl="https://picsum.photos/500/250/?image=1002" ncClickBorderColor="black" ncHoverBorderColor="black"
        dataModelForDynamicType="string" position="absolute" top="42.642755924772615%" left="47.32330827067669%"
        id="98a3c474-1647-42bf-be9f-a47a4bbedaf2"
        v-bind:style="{'width':'','height':'','fontSize':'7.428px','maxWidth':'','minWidth':'','boxShadow':'','fontStyle':'normal','marginTop':'0px','maxHeight':'','minHeight':'','fontFamily':'OpenSans-Bold,Open Sans','marginLeft':'0px','paddingTop':'0px','textShadow':'','visibility':'visible','marginRight':'0px','paddingLeft':'0px','marginBottom':'0px','paddingRight':'0px','paddingBottom':'0px','borderTopWidth':'0px','borderLeftWidth':'0px','borderRightWidth':'0px','borderBottomWidth':'0px','borderTopLeftRadius':'0px','borderTopRightRadius':'0px','borderBottomLeftRadius':'0px','borderBottomRightRadius':'0px','zIndex':2}"/>
    </NucGridCell>
  </NucGridPage>
</template>
<script>
export default {
  name: 'Screen1',
  data() {
    return {};
  },
  props: {},
  created() {},
  mounted() {},
  computed: {},
  methods: {},
  watch: {},
};
</script>

<style scoped></style>